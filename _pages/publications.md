---
permalink: /publications/
title: "Publications"
excerpt: "All publications"
author_profile: true
---

{%- comment -%}
Everything lives in _data/publications.yaml; this page renders all of it grouped
by year, with a sticky year index on the right.

Year order comes from `uniq | sort | reverse`. Because Ruby sorts strings
bytewise and digits sort before letters, that yields "Preprint" first and then
the numbered years descending — no hardcoded year list to maintain.
{%- endcomment -%}
{% assign years = site.data.publications.papers | map: "year" | uniq | sort | reverse %}

<div class="section-head">
  <h1 id="-all-publications">📝 All Publications</h1>
  <a class="all-pubs-link" href="{{ '/#-publications' | relative_url }}">&laquo; Back to home</a>
</div>

<div class="pub-layout">
<div class="pub-main">
{% for y in years %}
<h2 class="pub-year-heading" id="year-{{ y | slugify }}">{{ y }}</h2>
<table style="border-collapse:collapse; border:none; width:100%;">
{% for p in site.data.publications.papers %}{% if p.year == y %}{% include pub-entry.html paper=p %}{% endif %}{% endfor %}
</table>
{% endfor %}
</div>
<nav class="pub-year-nav" aria-label="Jump to year">
<ul>
{% for y in years %}
<li><a href="#year-{{ y | slugify }}">{{ y }}</a></li>
{% endfor %}
</ul>
</nav>
</div>

<script>
// Highlight the year currently in view. Purely decorative: if anything here
// fails, the anchor links above still work on their own.
(function () {
  var nav = document.querySelector('.pub-year-nav');
  if (!nav || !('IntersectionObserver' in window)) return;

  var links = {};
  Array.prototype.forEach.call(nav.querySelectorAll('a'), function (a) {
    links[a.getAttribute('href').slice(1)] = a;
  });

  var headings = document.querySelectorAll('.pub-year-heading');
  if (!headings.length) return;

  var visible = {};
  var observer = new IntersectionObserver(function (entries) {
    entries.forEach(function (e) { visible[e.target.id] = e.isIntersecting; });

    var current = null;
    Array.prototype.forEach.call(headings, function (h) {
      if (!current && visible[h.id]) current = h.id;
    });
    if (!current) return;

    Object.keys(links).forEach(function (id) {
      links[id].classList.toggle('is-active', id === current);
    });
  }, { rootMargin: '-10% 0px -70% 0px' });

  Array.prototype.forEach.call(headings, function (h) { observer.observe(h); });
})();
</script>

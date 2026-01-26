---
permalink: /
title: "About Me"
excerpt: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a PhD student at <a href="https://blender.cs.illinois.edu/" style="color: #7289da; text-decoration: none;">Blender Lab</a> at University of Illinois, Urbana-Champaign (UIUC), currently advised by Prof. <a href="https://blender.cs.illinois.edu/hengji.html" style="color: #7289da; text-decoration: none;">Heng Ji</a>. I obtained my Master's from the Graduate School of AI at KAIST, under the supervision of Prof. <a href="http://www.sungjuhwang.com/" style="color: #7289da; text-decoration: none;">Sung Ju Hwang</a>. If you are interested in collaborating with me on research projects, please contact me! Here is my <a href="https://drive.google.com/file/d/1WPAKJlVjXd3UItwzdtuC9zdM2vN9e8K3/view?usp=sharing" style="color: #7289da; text-decoration:none">CV</a>.

My primary research interest includes:
- Visual Perception Capability of Multimodal Large Language Models (MLLMs)
- Trustworthiness of MLLM-powered Framework (e.g., Embodied Agents, RAG)
- Model Interpretability & Robustness


# 🔥 News
- *2026.01*: &nbsp;🎉🎉 Four papers accepted to **ICLR 2026**, one paper accepted to **ACM 2026**!
- *2025.11*: &nbsp;🤘🤘 Passed Qual Exam! Now, I'm a **Ph.D Candidate**!
- *2025.09*: &nbsp;🎉🎉 One paper accepted to **NeurIPS 2025 (Spotlight)** 
- *2025.08*: &nbsp;🎉🎉 Awarded the **Capital One Illinois Center for Generative AI Safety, Knowledge Systems, and Cyber Security (ASKS) Fellowship Program**!
- *2025.05*: &nbsp;🎉🎉 One paper accepted to **ACL 2025** 
- *2025.01*: &nbsp;🎉🎉 Excited to start Machine Learning Research Internship at **Apple** from Summer 2025!
- *2024.08*: &nbsp;🤘🤘 Excited to start my Ph.D. program at **UIUC**! 
- *2023.09*: &nbsp;🎉🎉 Two papers accepted to **NeurIPS 2023 Conference** 
- *2023.06*: &nbsp;🎉🎉 One paper accepted to **ICML 2023 AdvML-Frontiers' Workshop** 
- *2022.08*: &nbsp;🎉🎉 Two papers accepted to **NeurIPS 2022 ML Safety Workshop**

# 📝 Publications 

<table style="border-collapse:collapse; border:none; width:100%;">
  <tr style="border:none;">
    <td style="width:260px; vertical-align:top; border:none; padding:8px 0;">
      <img src="/assets/imgs/narrative_teaser.png" width="260">
    </td>
    <td style="vertical-align:top; border:none; padding-left:16px; width:75%;">
      <strong>NarrativeTrack: Evaluating Video Language Models Beyond the Frame</strong><br/>
      <a href="https://arxiv.org/abs/2601.01095">[paper]</a>  
      <a href="https://machinelearning.apple.com/research/narrativetrack">[Apple Blog]</a><br/>
      Hyeonjeong Ha, Jinjin Ge, Bo Feng, Kaixin Ma, Gargi Chakraborty<br/>
      <span style="color:purple">UnderReview</span> 
    </td>
  </tr>
  <tr style="border:none;">
    <td style="width:260px; vertical-align:top; border:none; padding:8px 0;">
      <img src="/assets/imgs/mmpoisonrag_teaser.png" width="260">
    </td>
    <td style="vertical-align:top; border:none; padding-left:16px; width:75%;">
      <strong>MM-PoisonRAG: Disrupting Multimodal RAG with Local and Global Poisoning Attacks</strong><br/>
      <a href="https://arxiv.org/abs/2502.17832">[paper]</a><br/>
      <strong>Hyeonjeong Ha</strong>*, Qiusi Zhan*, Jeonghwan Kim, Dimitrios Bralios, Saikrishna Sanniboina, 
      Nanyun Peng, Kai-wei Chang, Heng Ji 
      <em>(* equal contribution)</em><br/>
      <span style="color:purple">UnderReview</span>
    </td>
  </tr>
  <tr style="border:none;">
    <td style="width:260px; vertical-align:top; border:none; padding:8px 0;">
      <img src="/assets/imgs/beat_teaser.png" width="260">
    </td>
    <td style="vertical-align:top; border:none; padding-left:16px; width:75%;">
      <strong>Visual Backdoor Attacks on MLLM Embodied Decision Making via Contrastive Trigger Learning</strong><br/>
      <a href="https://arxiv.org/abs/2510.27623">[paper]</a>
      <a href="https://zqs1943.github.io/BEAT/">[page]</a><br/>
      Qiusi Zhan*, <strong>Hyeonjeong Ha</strong>*, Rui Yang, Sirui Xu, Hanyang Chen, Liangyan Gui, 
      Yu-Xiong Wang, Huan Zhang, Heng Ji, Daniel Kang 
      <em>(* equal contribution)</em><br/>
      <span style="color:purple">ICLR 2026</span>
    </td>
  </tr>
  <tr style="border:none;">
    <td style="width:260px; vertical-align:top; border:none; padding:8px 0;">
      <img src="/assets/imgs/papo_teaser.png" width="260">
    </td>
    <td style="vertical-align:top; border:none; padding-left:16px;width:75%;">
      <strong>PAPO: Perception-Aware Policy Optimization for Multimodal Reasoning</strong><br/>
      <a href="https://arxiv.org/abs/2507.06448">[paper]</a>
      <a href="https://mikewangwzhl.github.io/PAPO/">[page]</a><br/>
      Zhenhailong Wang, Xuehang Guo, Sofia Stoica, Haiyang Xu, Hongru Wang, 
      <strong>Hyeonjeong Ha</strong>, Xiusi Chen, Yangyi Chen, Ming Yan, Fei Huang, Heng Ji 
      <em>(* equal contribution)</em><br/>
      <span style="color:purple">ICLR 2026</span>
    </td>
  </tr>
  <tr style="border:none;">
    <td style="width:260px; vertical-align:top; border:none; padding:8px 0;">
      <img src="/assets/imgs/ebwm_teaser.png" width="260">
    </td>
    <td style="vertical-align:top; border:none; padding-left:16px; width:75%;">
      <strong>Energy-Based Transformers are Scalable Learners and Thinkers</strong><br/>
      <a href="https://arxiv.org/abs/2507.02092">[paper]</a>
      <a href="https://alexiglad.github.io/blog/2025/ebt/">[blog]</a><br/>
      Alexi Gladstone, Ganesh Nanduru, Md Mofijul Islam, Peixuan Han, <strong>Hyeonjeong Ha</strong>, 
      Aman Chadha, Yilun Du, Heng Ji, Jundong Li, Tariq Iqbal<br/>
      <span style="color:purple">ICLR 2026</span>
    </td>
  </tr>
  <tr style="border:none;">
    <td style="width:260px; vertical-align:top; border:none; padding:8px 0;">
      <img src="/assets/imgs/imgwarp_teaser.png" width="260">
    </td>
    <td style="vertical-align:top; border:none; padding-left:16px; width:75%;">
      <strong>Constructive Distortion: Multimodal LLMs with Test-Time Image Warping</strong><br/>
      <a href="https://arxiv.org/html/2510.09741v1">[paper]</a><br/>
      Dwip Dalal, Gautam Vashishtha, Utkarsh Mishra, Jeonghwan Kim, Madhav Kanda, 
      <strong>Hyeonjeong Ha</strong>, Svetlana Lazebnik, Heng Ji, Unnat Jain<br/>
      <span style="color:purple">ICLR 2026</span>
    </td>
  </tr>
  <tr style="border:none;">
    <td style="width:260px; vertical-align:top; border:none; padding:8px 0;">
      <img src="/assets/imgs/mustread_teaser.png" width="260">
    </td>
    <td style="vertical-align:top; border:none; padding-left:16px; width:75%;">
      <strong>Must Read: A Systematic Survey of Computational Persuasion</strong><br/>
      <a href="https://www.arxiv.org/abs/2505.07775">[paper]</a><br/>
      Nimet Beyza Bozdag, Shuhaib Mehri, Xiaocheng Yang, <strong>Hyeonjeong Ha</strong>, Zirui Cheng, 
      Esin Durmus, Jiaxuan You, Heng Ji, Gokhan Tur, Dilek Hakkani-Tür<br/>
      <span style="color:purple">UnderReview</span>
    </td>
  </tr>
  <tr style="border:none;">
    <td style="width:260px; vertical-align:top; border:none; padding:8px 0;">
      <img src="/assets/imgs/partonomy_teaser.png" width="260">
    </td>
    <td style="vertical-align:top; border:none; padding-left:16px; width:75%;">
      <strong>PARTONOMY: Large Multimodal Models with Part-Level Visual Understanding</strong><br/>
      <a href="https://arxiv.org/abs/2505.20759">[paper]</a><br/>
      Ansel Blume, Jeonghwan Kim, <strong>Hyeonjeong Ha</strong>, Elen Chatikyan, Xiaomeng Jin, 
      Khanh Duy Nguyen, Nanyun Peng, Kai-Wei Chang, Derek Hoiem, Heng Ji<br/>
      <span style="color:purple">NeurIPS 2025</span> <span style="color:red">(Spotlight)</span>
    </td>
  </tr>
  <tr style="border:none;">
    <td style="width:260px; vertical-align:top; border:none; padding:8px 0;">
      <img src="/assets/imgs/synthia_teaser.png" width="260">
    </td>
    <td style="vertical-align:top; border:none; padding-left:16px; width:75%;">
      <strong>SYNTHIA: Novel Concept Design with Affordance Composition</strong><br/>
      <a href="https://arxiv.org/abs/2502.17793">[paper]</a>
      <a href="https://synthia-uiuc.github.io/synthia.github.io/">[page]</a><br/>
      <strong>Hyeonjeong Ha</strong>*, Xiaomeng Jin*, Jeonghwan Kim, Jiateng Liu, Zhenhailong Wang,
      Khanh Duy Nguyen, Ansel Blume, Nanyun Peng, Kai-Wei Chang, Heng Ji
      <em>(* equal contribution)</em><br/>
      <span style="color:purple">ACL 2025 (Main)</span>
    </td>
  </tr>
  <tr style="border:none;">
    <td style="width:260px; vertical-align:top; border:none; padding:8px 0;">
      <img src="/assets/imgs/ronas_teaser.png" width="260">
    </td>
    <td style="vertical-align:top; border:none; padding-left:16px; width:75%;">
      <strong>Generalizable Lightweight Proxy for Robust NAS against Diverse Perturbations</strong><br/>
      <a href="https://arxiv.org/abs/2306.05031">[paper]</a><br/>
      <strong>Hyeonjeong Ha</strong>*, Minseon Kim*, Sung Ju Hwang 
      <em>(* equal contribution)</em><br/>
      <span style="color:purple">NeurIPS 2023</span>
    </td>
  </tr>
  <tr style="border:none;">
    <td style="width:260px; vertical-align:top; border:none; padding:8px 0;">
      <img src="/assets/imgs/tasl_teaser.png" width="260">
    </td>
    <td style="vertical-align:top; border:none; padding-left:16px; width:75%;">
      <strong>Effective Targeted Attacks for Adversarial Self-Supervised Learning</strong><br/>
      <a href="https://arxiv.org/abs/2210.10482">[paper]</a><br/>
      Minseon Kim, <strong>Hyeonjeong Ha</strong>, Sooel Son, Sung Ju Hwang<br/>
      <span style="color:purple">NeurIPS 2023</span>
    </td>
  </tr>
  <tr style="border:none;">
    <td style="width:260px; vertical-align:top; border:none; padding:8px 0;">
      <img src="/assets/imgs/marvl_teaser.png" width="260">
    </td>
    <td style="vertical-align:top; border:none; padding-left:16px; width:75%;">
      <strong>Few-shot Transferable Robust Representation Learning via Bilevel Attacks</strong><br/>
      <a href="https://arxiv.org/abs/2210.10485">[paper]</a><br/>
      Minseon Kim*, <strong>Hyeonjeong Ha</strong>*, Sung Ju Hwang 
      <em>(* equal contribution)</em><br/>
      <span style="color:purple">NeurIPS 2022 ML Safety Workshop</span>
    </td>
  </tr>
</table>

<!--
| <img src="/assets/imgs/mmpoisonrag_teaser.png" width="300" height="150"> | **MM-PoisonRAG: Disrupting Multimodal RAG with Local and Global Poisoning Attacks**<br/>[[paper]](https://arxiv.org/abs/2502.17832)<br/>**Hyeonjeong Ha** *, Qiusi Zhan *, Jeonghwan Kim, Dimitrios Bralios, Saikrishna Sanniboina, Nanyun Peng, Kai-wei Chang, Heng Ji (\*: equal contribution)<br/><span style="color:purple">UnderReview</span> |
| <img src="/assets/imgs/beat_teaser.png" width="300" height="150"> | **Visual Backdoor Attacks on MLLM Embodied Decision Making via Contrastive Trigger Learning**<br/>[[paper]](https://arxiv.org/abs/2510.27623) [[page]](https://zqs1943.github.io/BEAT/)<br/>Qiusi Zhan *, **Hyeonjeong Ha** *, Rui Yang, Sirui Xu, Hanyang Chen, Liangyan Gui, Yu-Xiong Wang, Huan Zhang, Heng Ji, Daniel Kang (\*: equal contribution)<br/><span style="color:purple">UnderReview</span> |
| <img src="/assets/imgs/papo_teaser.png" width="300" height="150"> | **PAPO: Perception-Aware Policy Optimization for Multimodal Reasoning**<br/>[[paper]](https://arxiv.org/abs/2507.06448)  [[page]](https://mikewangwzhl.github.io/PAPO/)<br/>Zhenhailong Wang, Xuehang Guo, Sofia Stoica, Haiyang Xu, Hongru Wang, **Hyeonjeong Ha**, Xiusi Chen, Yangyi Chen, Ming Yan, Fei Huang, Heng Ji (\*: equal contribution)<br/><span style="color:purple">UnderReview</span> |
| <img src="/assets/imgs/ebwm_teaser.png" width="300" height="150"> | **Energy-Based Transformers are Scalable Learners and Thinkers**<br/>[[paper]](https://arxiv.org/abs/2507.02092) [[blog]](https://alexiglad.github.io/blog/2025/ebt/) <br/>Alexi Gladstone, Ganesh Nanduru, Md Mofijul Islam, Peixuan Han, **Hyeonjeong Ha**, Aman Chadha, Yilun Du, Heng Ji, Jundong Li, Tariq Iqbal<br/><span style="color:purple">UnderReview</span> |
| <img src="/assets/imgs/imgwarp_teaser.png" width="300" height="150"> | **Constructive Distortion: Multimodal LLMs with Test-Time Image Warping**<br/>[[paper]](https://arxiv.org/html/2510.09741v1) <br/>Dwip Dalal, Gautam Vashishtha, Utkarsh Mishra, Jeonghwan Kim, Madhav Kanda, **Hyeonjeong Ha**, Svetlana Lazebnik, Heng Ji, Unnat Jain<br/><span style="color:purple">UnderReview</span> |
| <img src="/assets/imgs/mustread_teaser.png" width="300" height="150"> | **Must Read: A Systematic Survey of Computational Persuasion**<br/>[[paper]](https://www.arxiv.org/abs/2505.07775)<br/>Nimet Beyza Bozdag, Shuhaib Mehri, Xiaocheng Yang, **Hyeonjeong Ha**, Zirui Cheng, Esin Durmus, Jiaxuan You, Heng Ji, Gokhan Tur, Dilek Hakkani-Tür<br/><span style="color:purple">UnderReview</span> |
| <img src="/assets/imgs/ronas_teaser.png" width="300" height="150"> | **Generalizable Lightweight Proxy for Robust NAS against Diverse Perturbations**<br/>[[paper]](https://arxiv.org/abs/2306.05031)<br/>**Hyeonjeong Ha** *, Minseon Kim *, Sung Ju Hwang (\*: equal contribution)<br/><span style="color:purple">NeurIPS 2023</span> |
| <img src="/assets/imgs/tasl_teaser.png" width="300" height="150"> | **Effective Targeted Attacks for Adversarial Self-Supervised Learning**<br/>[[paper]](https://arxiv.org/abs/2210.10482)<br/>Minseon Kim, **Hyeonjeong Ha**, Sooel Son, Sung Ju Hwang<br/><span style="color:purple">NeurIPS 2023</span> |
| <img src="/assets/imgs/marvl_teaser.png" width="300" height="150"> | **Few-shot Transferable Robust Representation Learning via Bilevel Attacks**<br/>[[paper]](https://arxiv.org/abs/2210.10485)<br/>Minseon Kim *, **Hyeonjeong Ha** *, Sung Ju Hwang (\*: equal contribution)<br/><span style="color:purple">**NeurIPS**</span> 2022 ML Safety Workshop |

- <font size="3">PARTONOMY: Large Multimodal Models with Part-Level Visual Understanding</font>
[[paper]](https://arxiv.org/abs/2505.20759) \
Ansel Blume, Jeonghwan Kim, **Hyeonjeong Ha**, Elen Chatikyan, Xiaomeng Jin, Khanh Duy Nguyen, Nanyun Peng, Kai-Wei Chang, Derek Hoiem, Heng Ji  \
<span style="color:purple">NeurIPS 2025</span> <span style="color:red">(Spotlight)</span>

- <font size="3">SYNTHIA: Novel Concept Design with Affordance Composition</font> 
[[paper]](https://arxiv.org/abs/2502.17793) [[page]](https://synthia-uiuc.github.io/synthia.github.io/)\
**Hyeonjeong Ha** *, Xiaomeng Jin *, Jeonghwan Kim, Jiateng Liu, Zhenhailong Wang, Khanh Duy Nguyen, Ansel Blume, Nanyun Peng, Kai-wei Chang, Heng Ji (\*: equal contribution)  \
<span style="color:purple">ACL 2025 (Main)</span>

- <font size="3">MM-PoisonRAG: Disrupting Multimodal RAG with Local and Global Poisoning Attacks</font> 
[[paper]](https://arxiv.org/abs/2502.17832) \
**Hyeonjeong Ha** *, Qiusi Zhan *, Jeonghwan Kim, Dimitrios Bralios, Saikrishna Sanniboina, Nanyun Peng, Kai-wei Chang, Heng Ji (\*: equal contribution)  \
<span style="color:purple">preprint</span> 

- <font size="3">Visual Backdoor Attacks on MLLM Embodied Decision Making via Contrastive Trigger Learning</font>
[[paper]](https://arxiv.org/abs/2510.27623) [[page]](https://zqs1943.github.io/BEAT/)\
Qiusi Zhan *, **Hyeonjeong Ha** *, Rui Yang, Sirui Xu, Hanyang Chen, Liangyan Gui, Yu-Xiong Wang, Huan Zhang, Heng Ji, Daniel Kang (\*: equal contribution) \
<span style="color:purple">preprint</span> 

- <font size="3">PAPO: Perception-Aware Policy Optimization for Multimodal Reasoning</font>
[[paper]](https://arxiv.org/abs/2507.06448)  [[page]](https://mikewangwzhl.github.io/PAPO/)\
Zhenhailong Wang, Xuehang Guo, Sofia Stoica, Haiyang Xu, Hongru Wang, **Hyeonjeong Ha**, Xiusi Chen, Yangyi Chen, Ming Yan, Fei Huang, Heng Ji  \
<span style="color:purple">preprint</span>

- <font size="3">Energy-Based Transformers are Scalable Learners and Thinkers</font>
[[paper]](https://arxiv.org/abs/2507.02092) [[blog]](https://alexiglad.github.io/blog/2025/ebt/) \
Alexi Gladstone, Ganesh Nanduru, Md Mofijul Islam, Peixuan Han, **Hyeonjeong Ha**, Aman Chadha, Yilun Du, Heng Ji, Jundong Li, Tariq Iqbal  \
<span style="color:purple">preprint</span>

- <font size="3">Constructive Distortion: Multimodal LLMs with Test-Time Image Warping</font> 
[[paper]](https://arxiv.org/html/2510.09741v1) \
Dwip Dalal, Gautam Vashishtha, Utkarsh Mishra, Jeonghwan Kim, Madhav Kanda, **Hyeonjeong Ha**, Svetlana Lazebnik, Heng Ji, Unnat Jain  \
<span style="color:purple">preprint</span>

- <font size="3">Must Read: A Systematic Survey of Computational Persuasion</font> 
[[paper]](https://www.arxiv.org/abs/2505.07775) \
Nimet Beyza Bozdag, Shuhaib Mehri, Xiaocheng Yang, **Hyeonjeong Ha**, Zirui Cheng, Esin Durmus, Jiaxuan You, Heng Ji, Gokhan Tur, Dilek Hakkani-Tür  \
<span style="color:purple">preprint</span>

- <font size="3">Generalizable Lightweight Proxy for Robust NAS against Diverse Perturbations</font> 
[[paper]](https://arxiv.org/abs/2306.05031) \
**Hyeonjeong Ha** *, Minseon Kim *, Sung Ju Hwang (\*: equal contribution)  \
<span style="color:purple">**NeurIPS**</span> 2023 \
<span style="color:purple">**ICML**</span> 2023 The 2ND New Frontiers in Adversarial Machine Learning Workshop

- <font size="3">Effective Targeted Attacks for Adversarial Self-Supervised Learning</font>
[[paper]](https://arxiv.org/abs/2210.10482) \
Minseon Kim, **Hyeonjeong Ha**, Sooel Son, Sung Ju Hwang \
<span style="color:purple">**NeurIPS**</span> 2023

- <font size="3">Few-shot Transferable Robust Representation Learning via Bilevel Attacks</font> 
[[paper]](https://arxiv.org/abs/2210.10485) \
Minseon Kim *, **Hyeonjeong Ha** *, Sung Ju Hwang (\*: equal contribution) \
<span style="color:purple">**NeurIPS**</span> 2022 ML Safety Workshop 
-->
<!--# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. -->

# 📖 Educations
- *2024.08 - Present*, Ph.D in Computer Science, <a href="https://blender.cs.illinois.edu/" style="color: #7289da; text-decoration: none;">UIUC</a>.
- *2022.02 - 2024.02*, M.S. in Graduate School of AI, <a href="https://www.kaist.ac.kr/en/" style="color: #7289da; text-decoration: none;">KAIST</a>.
- *2017.02 - 2022.02*, B.S. in Computer Science (major) and Bio & Brain Engineering (minor), <a href="https://www.kaist.ac.kr/en/" style="color: #7289da; text-decoration: none;">KAIST</a>.

<!--# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)-->

# 💻 Work Experience
<table style="border-collapse:collapse; border:none; width:100%;">
  <tr style="border:none;">
    <td style="width:180px; vertical-align:top; border:none; padding:8px;">
      <img src="/assets/imgs/apple_logo.jpeg" width="150">
    </td>
    <td style="vertical-align:top; border:none; padding-left:16px; width:50%;">
      <strong>Apple</strong><br/>
      Machine Learning Research Intern
    </td>
    <td style="vertical-align:top; text-align:right; border:none; width:30%;">
      <em>Seattle, WA, USA</em><br/>
      May 2025 – Aug 2025
    </td>
  </tr>
  
  <tr style="border:none;">
    <td style="width:180px; vertical-align:top; border:none; padding:8px 0;">
      <img src="/assets/imgs/samsung_logo.png" width="150">
    </td>
    <td style="vertical-align:top; border:none; padding-left:16px; width:50%;">
      <strong><a href="https://research.samsung.com/" style="color: #7289da; text-decoration: none;">Samsung Research</a></strong><br/>
      Machine Learning Engineer, Full-Time
    </td>
    <td style="vertical-align:top; text-align:right; border:none; width:30%;">
      <em>Seoul, South Korea</em><br/>
      Feb 2024 – Jul 2024
    </td>
  </tr>

  <tr style="border:none;">
    <td style="width:180px; vertical-align:top; border:none; padding:8px 0;">
      <img src="/assets/imgs/naver_logo.png" width="150">
    </td>
    <td style="vertical-align:top; border:none; padding-left:16px; width:50%;">
      <strong><a href="https://developers.naver.com/main/" style="color: #7289da; text-decoration: none;">NAVER</a></strong><br/>
      Software Developer Intern
    </td>
    <td style="vertical-align:top; text-align:right; border:none; width:30%;">
      <em>Seongnam, South Korea</em><br/>
      Sep 2020 – Feb 2021
    </td>
  </tr>

  <tr style="border:none;">
    <td style="width:180px; vertical-align:top; border:none; padding:8px 0;">
      <img src="/assets/imgs/kaist_logo.png" width="150">
    </td>
    <td style="vertical-align:top; border:none; padding-left:16px; width:50%;">
      <strong><a href="https://www.kixlab.org/" style="color: #7289da; text-decoration: none;">KIXLAB</a></strong><br/>
      Undergraduate Research Intern<br/>
      Advisor: Prof. <a href="https://juhokim.com/" style="color: #7289da; text-decoration: none;">Juho Kim</a>
    </td>
    <td style="vertical-align:top; text-align:right; border:none; width:30%;">
      <em>Daejeon, South Korea</em><br/>
      Jun 2020 – Aug 2020
    </td>
  </tr>

  <tr style="border:none;">
    <td style="width:180px; vertical-align:top; border:none; padding:8px 0;">
      <img src="/assets/imgs/h2k_logo.png" width="150">
    </td>
    <td style="vertical-align:top; border:none; padding-left:16px; width:50%;">
      <strong><a href="https://www.sojunghangeul.com/home/main" style="color: #7289da; text-decoration: none;">H2K</a></strong><br/>
      Software Developer Intern
    </td>
    <td style="vertical-align:top; text-align:right; border:none; width:30%;">
      <em>Daejeon, South Korea</em><br/>
      Jun 2019 – Dec 2019
    </td>
  </tr>
</table>

<!--
- *2025.05 - 2025.08*, Machine Learning Research Intern at **Apple**, AI/ML Data & Machine Learning Innovation team, Seattle, WA, USA.
- *2024.02 - 2024.07*, Full-time Employee at <a href="https://research.samsung.com/" style="color: #7289da; text-decoration: none;">Samsung Research</a>, Language Intelligence Team, Seoul, South Korea. 
- *2020.09 - 2021.02*, Developer Intern at <a href="https://developers.naver.com/main/" style="color: #7289da; text-decoration: none;">NAVER</a>, Seongnam, South Korea.
- *2020.06 - 2020.08*, Undergraduate Research Intern at <a href="https://www.kixlab.org/" style="color: #7289da; text-decoration: none;">KIXLAB</a>, KAIST, Daejeon, South Korea. Prof: <a href="https://juhokim.com/" style="color: #7289da; text-decoration: none;">Juho Kim</a>
- *2019.06 - 2019.12*, Developer Intern at <a href="https://www.sojunghangeul.com/home/main" style="color: #7289da; text-decoration: none;">H2K</a>, Daejeon, South Korea.-->


# 👩‍💻 Academic Service
- *Reviewer*: ICML (2024, 2023), NeurIPS (2023)

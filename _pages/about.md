---
permalink: /
title: ""
excerpt: ""
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


I am a master's student in Software Engineering at Beihang University, advised by <a href='https://yuqian1023.github.io/'>Prof. Qian Yu</a>. I build multimodal models that write <strong>visual code</strong>, producing editable SVG graphics and vector animations instead of pixels. I am currently working on <strong>RL post-training</strong> for the <a href='https://studio.dots.ai/dots/dots3-zh.html'><strong>dots</strong></a> foundation models at Xiaohongshu (rednote) through the ACE Top Talent Program.

<div class="glance">
  <div class="glance-card">
    <a href="https://yukinonooo.github.io/RenderInTheLoopProject/"><img src="images/covers/vsf.png" loading="lazy" alt="Render-in-the-Loop SVG generation"></a>
    <div class="glance-body">
      <div class="glance-title">🎨 SVG Code Generation</div>
      <div class="glance-desc">Text → editable SVG programs</div>
      <div class="glance-links">
        <span class="gl-item"><a href="https://yukinonooo.github.io/RenderInTheLoopProject/">Render-in-the-Loop</a><span>ECCV'26</span></span>
        <span class="gl-item"><a href="https://ximinng.github.io/LLM4SVGProject/">LLM4SVG</a><span>CVPR'25</span></span>
        <span class="gl-item"><a href="https://github.com/Yukinonooo/SVGFaith">SVGFaith</a><span>arXiv'26</span></span>
      </div>
    </div>
  </div>
  <div class="glance-card">
    <a href="https://yukinonooo.github.io/VAnimProject/" class="glance-anim">
      <video src="images/vanim/2.mp4" autoplay muted loop playsinline></video>
      <video src="images/vanim/4.mp4" autoplay muted loop playsinline></video>
      <video src="images/vanim/17.mp4" autoplay muted loop playsinline></video>
      <video src="images/vanim/18.mp4" autoplay muted loop playsinline></video>
    </a>
    <div class="glance-body">
      <div class="glance-title">🎬 Vector Animation Generation</div>
      <div class="glance-desc">Text → structure-preserving SVG animation</div>
      <div class="glance-links">
        <span class="gl-item"><a href="https://yukinonooo.github.io/VAnimProject/">VAnim</a><span>ICML'26</span></span>
        <span class="gl-item"><a href="https://hjc-owo.github.io/GroupSketchProject/">GroupSketch</a><span>MM'25</span></span>
      </div>
    </div>
  </div>
</div>


# 🔥 News
- *2026.11*: &nbsp;🏅 Awarded the **Shen Yuan Medal**, the highest honor for students at Beihang University (10 recipients).
- *2026.11*: &nbsp;🚀 We released <a href='https://github.com/Yukinonooo/SVGFaith'>SVGFaith</a>, a meta-evaluation benchmark for Text-to-SVG faithfulness metrics.
- *2026.06*: &nbsp;🎉🎉 Our paper <a href='https://yukinonooo.github.io/RenderInTheLoopProject/'>Render-in-the-Loop</a> has been accepted by ECCV 2026!
- *2026.05*: &nbsp;🎉🎉 Our paper <a href='https://yukinonooo.github.io/VAnimProject/'>VAnim</a> has been accepted by ICML 2026!
- *2025.07*: &nbsp;🎉🎉 Our paper <a href='https://hjc-owo.github.io/GroupSketchProject/'>GroupSketch</a> has been accepted by ACM MM 2025! 
- *2025.02*: &nbsp;🎉🎉 Our paper <a href='https://ximinng.github.io/LLM4SVGProject/'>LLM4SVG</a> has been accepted by CVPR 2025!


# 📝 Publications

<!-- paper 6 -->
<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge badge-eccv">ECCV 2026</div><img src='images/covers/vsf.png' loading="lazy" alt="Render-in-the-Loop"></div></div>
<div class='paper-box-text' markdown="1">


[Render-in-the-Loop: Vector Graphics Generation via Visual Self-Feedback](files/Render_in_the_Loop_ECCV2026.pdf)

Guotao Liang, Zhangcheng Wang, Juncheng Hu, Haitao Zhou, Ziteng Xue, Jing Zhang, Dong Xu, Qian Yu<sup>†</sup>

<span class="paper-note"><sup>†</sup> Corresponding author.</span>

[![paper](https://img.shields.io/badge/Paper-PDF-red.svg)](files/Render_in_the_Loop_ECCV2026.pdf)
[![project](https://img.shields.io/badge/%F0%9F%8F%A0%20Homepage-Render--in--the--Loop-orange.svg)](https://yukinonooo.github.io/RenderInTheLoopProject/)
[![arXiv](https://img.shields.io/badge/arXiv-2604.20730-b31b1b.svg)](https://arxiv.org/abs/2604.20730)

<b><u>TL;DR:</u></b> Render-in-the-Loop closes the loop for **SVG generation** by rendering intermediate code states back into the MLLM, enabling **Visual Self-Feedback** training and **Render-and-Verify** inference for cleaner, more reliable vector graphics.

European Conference on Computer Vision (ECCV), 2026.

📄 [**Paper**](files/Render_in_the_Loop_ECCV2026.pdf) |
🌐 [**Project**](https://yukinonooo.github.io/RenderInTheLoopProject/) |
📝 [**arXiv**](https://arxiv.org/abs/2604.20730)
</div>
</div>

<!-- paper 5 -->
<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">ICML 2026</div><img src='images/covers/vanim.png' loading="lazy" alt="VAnim"></div></div>
<div class='paper-box-text' markdown="1">


[VAnim: Rendering-Aware Sparse State Modeling for Structure-Preserving Vector Animation](files/VAnim_ICML2026.pdf)

**Guotao Liang**, Zhangcheng Wang, Chuang Wang, Juncheng Hu, Haitao Zhou, Junhua Liu, Jing Zhang, Dong Xu, Qian Yu

[![paper](https://img.shields.io/badge/Paper-PDF-red.svg)](files/VAnim_ICML2026.pdf)
[![project](https://img.shields.io/badge/%F0%9F%8F%A0%20Homepage-VAnim-orange.svg)](https://yukinonooo.github.io/VAnimProject/)

<b><u>TL;DR:</u></b> VAnim formulates SVG animation as **sparse state updates** on a persistent DOM tree, combining identification-first motion planning with rendering-aware RL to generate **structure-preserving vector animations** from text.

International Conference on Machine Learning (ICML), 2026.

📄 [**Paper**](files/VAnim_ICML2026.pdf) |
🌐 [**Project**](https://yukinonooo.github.io/VAnimProject/)
</div>
</div>

<!-- paper 4 -->

<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">ACM MM 2025</div><img src='images/covers/groupsketch.png' loading="lazy" alt="GroupSketch"></div></div>
<div class='paper-box-text' markdown="1">


[Multi-Object Sketch Animation with Grouping and Motion Trajectory Priors](https://arxiv.org/abs/2508.15535)

**Guotao Liang**, Juncheng Hu, Ximing Xing, Jing Zhang, Qian Yu

[![project](https://img.shields.io/badge/%F0%9F%8F%A0%20Homepage-GroupSketch-orange.svg)](https://hjc-owo.github.io/GroupSketchProject/)
[![GitHub stars](https://img.shields.io/github/stars/Yukinonooo/GroupSketch?style=social)](https://github.com/Yukinonooo/GroupSketch)

<b><u>TL;DR:</u></b> GroupSketch synthesizes **multi-object sketch animations** with **grouping** and **motion trajectory** priors, enabling users to create complex animations with ease.

ACM International Conference on Multimedia, 2025.

🌐 [**Project**](https://hjc-owo.github.io/GroupSketchProject/) |
📁 [**Code**](https://github.com/Yukinonooo/GroupSketch)
</div>
</div>

<!-- paper 3 -->
<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/covers/llm4svg.png' loading="lazy" alt="LLM4SVG"></div></div>
<div class='paper-box-text' markdown="1">

[Empowering LLMs to Understand and Generate Complex Vector Graphics](https://arxiv.org/abs/2412.11102)

Ximing Xing, Juncheng Hu, **Guotao Liang**, Jing Zhang, Dong Xu, Qian Yu

[![project](https://img.shields.io/badge/%F0%9F%8F%A0%20Homepage-LLM4SVG-orange.svg)](https://ximinng.github.io/LLM4SVGProject/)
[![dataset](https://img.shields.io/badge/Dataset-SVGX_SFT_1M-ffcc00?logo=huggingface)](https://huggingface.co/datasets/xingxm/SVGX-SFT-1M)
[![](https://img.shields.io/github/stars/ximinng/LLM4SVG?style=social&label=Code+Stars)](https://github.com/ximinng/LLM4SVG)

<b><u>TL;DR:</u></b> LLM4SVG introduces learnable **SVG Semantic Tokens** and a large **SVGX-SFT dataset**, enabling LLMs to understand and generate complex vector graphics.

IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2025

🌐 [**Project**](https://ximinng.github.io/LLM4SVGProject/) |
📁 [**Code**](https://github.com/ximinng/LLM4SVG) |
🤗 [**SVGX-SFT-1M Dataset**](https://huggingface.co/datasets/xingxm/SVGX-SFT-1M)

</div>
</div>



# 🧪 Preprints

<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge badge-preprint">arXiv 2026</div><img src='images/svgfaith/teaser.png' loading="lazy" alt="SVGFaith"></div></div>
<div class='paper-box-text' markdown="1">

[SVGFaith: A Two-Layer Meta-Evaluation of Faithfulness Metrics for Text-to-SVG Generation](https://arxiv.org/abs/2611.06048)

**Guotao Liang**, Haitao Zhou, Biao Liu, Huanxuan Liao, Lingfeng Qiao, Qian-Wen Zhang, Qian Yu, Di Yin, Xing Sun

[![arXiv](https://img.shields.io/badge/arXiv-2611.06048-b31b1b.svg)](https://arxiv.org/abs/2611.06048)
[![GitHub stars](https://img.shields.io/github/stars/Yukinonooo/SVGFaith?style=social)](https://github.com/Yukinonooo/SVGFaith)
[![Benchmark](https://img.shields.io/badge/%F0%9F%A4%97%20Benchmark-SVGFaith-fcd022.svg)](https://huggingface.co/datasets/Yukinonooo/SVGFaith)

<b><u>TL;DR:</u></b> Does your Text-to-SVG metric actually prefer the more faithful SVG? SVGFaith tests this with **1,842 controlled contrastive pairs** over eight capability axes and **1,327 human comparisons** of real generator outputs, and proposes **SVGFaith-Score**, an interpretable metric that beats CLIP-style scores and VLM judges on both layers.

📝 [**arXiv**](https://arxiv.org/abs/2611.06048) |
📁 [**Code**](https://github.com/Yukinonooo/SVGFaith) |
🤗 [**Benchmark**](https://huggingface.co/datasets/Yukinonooo/SVGFaith) |
🤗 [**Decomposer**](https://huggingface.co/Yukinonooo/SVGFaith-Decomposer)
</div>
</div>

# 🎖 Honors & Awards
- *2026.11*: **Shen Yuan Medal** (the highest honor for students at Beihang University, 10 recipients), 沈元奖章（北航学生最高荣誉，10人）.
- *2026.11*: **Beijing Merit Student**, 北京市三好学生.
- *2026.10*: **National Scholarship**, 国家奖学金.

# 📖 Educations
- _2024.09 – Present_: **M.S. in Software Engineering**, School of Software, Beihang University



<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships

<div class="intern current">
  <div class="intern-head"><b>2026.09 – Present</b><i>·</i><a href="https://studio.dots.ai/dots/dots3-zh.html">dots</a>, Xiaohongshu (rednote)<i>·</i>Algorithm Intern, ACE Top Talent Program<i>·</i>Beijing, China</div>
  <div class="intern-title">Post-training for dots Foundation Models</div>
  <ul>
    <li>Working on <b>reinforcement learning (RL)</b> post-training for the dots foundation models.</li>
    <li>Main contributor to an <b>agent arena</b> that evaluates coding agents on real-life tasks such as Blender 3D interior design and video editing.</li>
    <li>Synthesizing <b>SFT data and training environments</b> for agentic tasks.</li>
  </ul>
</div>

<div class="intern">
  <div class="intern-head"><b>2026.06 – 2026.09</b><i>·</i><a href="https://youtu-tip.com/#llm">Tencent YouTu Lab</a><i>·</i>Algorithm Intern, Qingyun Program<i>·</i>Beijing, China</div>
  <div class="intern-title">Text-to-SVG Evaluation &amp; Self-Evolving Data</div>
  <ul>
    <li>Built <a href="https://github.com/Yukinonooo/SVGFaith"><b>SVGFaith</b></a>, a meta-evaluation benchmark and interpretable metric for Text-to-SVG faithfulness.</li>
    <li>Built a <b>multi-agent system based on recursive self-improvement (RSI)</b> that drives a self-evolving data flywheel.</li>
  </ul>
</div>

<div class="intern">
  <div class="intern-head"><b>2026.01 – 2026.06</b><i>·</i><a href="https://www.ubiquant.com/website/ai">Ubiquant Investment</a><i>·</i>Algorithm Intern, <a href="https://iquestlab.github.io/">iQuest LLM Team</a><i>·</i>Beijing, China</div>
  <div class="intern-title">Code Agents</div>
  <ul>
    <li>Worked on <b>code agent</b> training and post-training for the iQuest foundation large language models.</li>
  </ul>
</div>

<div class="intern">
  <div class="intern-head"><b>2025.05 – 2025.12</b><i>·</i><a href="https://www.4paradigm.com/">4Paradigm</a><i>·</i>Algorithm Intern<i>·</i>Beijing, China</div>
  <div class="intern-title">Vector Graphics Animation</div>
  <ul>
    <li>Conducted research on <b>multimodal large language models for vector graphics animation</b>.</li>
  </ul>
</div>

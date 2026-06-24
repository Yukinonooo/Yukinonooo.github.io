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


I am a master's student in Software Engineering at Beihang University, advised by <a href='https://yuqian1023.github.io/'>Prof. Qian Yu.</a> My research is centered on <strong>visual code generation</strong>: building models that generate structured, editable visual <strong>code</strong> rather than rasterized outputs. I work at the intersection of multimodal large language models, vector graphics, and generative modeling, with two primary research threads. The first is <strong>SVG code generation</strong>, where I study how models can understand, reason over, and synthesize vector graphics programs, with representative works including <a href='https://yukinonooo.github.io/RenderInTheLoopProject/'>Render-in-the-Loop</a> and <a href='https://ximinng.github.io/LLM4SVGProject/'>LLM4SVG</a>. The second is <strong>vector animation code generation</strong>, where I build models that generate temporally coherent, structure-preserving vector animations directly in code, represented by <a href='https://yukinonooo.github.io/VAnimProject/'>VAnim</a> and <a href='https://hjc-owo.github.io/GroupSketchProject/'>GroupSketch</a>.

More broadly, I am interested in turning code-centric multimodal models into practical systems for creation and interaction. Currently, I am a Qingyun Program Research Intern in the Pre-training Group at <a href='https://youtu-tip.com/#llm'>Tencent YouTu Lab</a>, working on <strong>native multimodal foundation large language models</strong> for vector graphics generation. My industry research focuses on applying MLLMs to <strong>visual code generation agents</strong>, and on building <strong>TTSScore</strong>, a trustworthy Text-to-SVG metric and benchmark for measuring the faithfulness between SVG outputs and text prompts. Previously, I worked on <strong>generative ranking and retrieval</strong> at <a href='https://yuanbao.tencent.com/'>Tencent Yuanbao</a>, and on <strong>code agents</strong> and <strong>search agents</strong> within the <a href='https://iquestlab.github.io/'><strong>iQuest foundation large language model team</strong></a> at <a href='https://www.ubiquant.com/website/ai'>Ubiquant Investment</a>. These experiences further strengthen my goal of pushing AI beyond visual understanding toward controllable, executable, and production-ready visual code generation systems.


# 🔥 News
- *2026.06*: &nbsp;🎉🎉 Our paper <a href='https://yukinonooo.github.io/RenderInTheLoopProject/'>Render-in-the-Loop</a> has been accepted by ECCV 2026!
- *2026.05*: &nbsp;🎉🎉 Our paper <a href='https://yukinonooo.github.io/VAnimProject/'>VAnim</a> has been accepted by ICML 2026!
- *2025.07*: &nbsp;🎉🎉 Our paper <a href='https://hjc-owo.github.io/GroupSketchProject/'>GroupSketch</a> has been accepted by ACM MM 2025! 
- *2025.02*: &nbsp;🎉🎉 Our paper <a href='https://ximinng.github.io/LLM4SVGProject/'>LLM4SVG</a> has been accepted by CVPR 2025!


# 📝 Publications

<!-- paper 6 -->
<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">ECCV 2026</div><img src='images/covers/vsf.png' loading="lazy" alt="Render-in-the-Loop"></div></div>
<div class='paper-box-text' markdown="1">


[Render-in-the-Loop: Vector Graphics Generation via Visual Self-Feedback](files/Render_in_the_Loop_ECCV2026.pdf)

**Guotao Liang**, Zhangcheng Wang, Juncheng Hu, Haitao Zhou, Ziteng Xue, Jing Zhang, Dong Xu, Qian Yu

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



<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Educations
- _2024.09 – Present_: **M.S. in Software Engineering**, School of Software, Beihang University



<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- **2026.06 – Present**, [Tencent YouTu Lab](https://youtu-tip.com/#llm), Research Intern, Qingyun Program, Pre-training Group — Beijing, China  
  Working on **native multimodal foundation large language models** for **vector graphics generation**, with a focus on **visual code generation agents** and **TTSScore**, a trustworthy Text-to-SVG metric and benchmark for evaluating faithfulness between SVG outputs and text prompts.

- **2026.03 – 2026.06**, [Ubiquant Investment](https://www.ubiquant.com/website/ai), Algorithm Intern, [iQuest Foundation Large Language Model Team](https://iquestlab.github.io/) — Beijing, China  
  Worked on **code agent** and **search agent** training/post-training within the **iQuest foundation large language model** team.

- **2025.10 – 2026.02**, [Tencent Yuanbao](https://yuanbao.tencent.com/), Algorithm Intern, Yuanbao Search Department — Beijing, China  
  Working on **generative ranking and retrieval** with **multimodal large language models**.

- **2025.05 – 2025.09**, [4Paradigm](https://www.4paradigm.com/), Research Intern — Beijing, China  
  Conducted research on **multimodal large language models for vector graphics animation**.

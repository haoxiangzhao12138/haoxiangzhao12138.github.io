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

# 📄 About Me

I am a master's student at the **Institute of Automation, Chinese Academy of Sciences (CASIA)**, affiliated with the **National Laboratory of Pattern Recognition**. I am supervised by [Prof. Haiyun Guo](https://people.ucas.edu.cn/~haiyun.guo) and under the leadership of [Prof. Jinqiao Wang](https://people.ucas.ac.cn/~jinqiaowang). I am also a member of the [Zidongtaichu Foundation Model Research Center](https://zky-dev.wair.ac.cn/). I am currently an intern at the **Wenxin (ERNIE Bot) team at Baidu**.

My research centers on two directions:
- **Multimodal Retrieval**: I explore reasoning-enhanced retrieval paradigms, fine-grained instance-level retrieval, and composed image retrieval. Representative works include TRACE, PLUME, REIR/CLARE, UniFGVC, WISER, and ReCALL.
- **Unified Understanding-Generation Models**: I investigate how to leverage generation capabilities to assist understanding in unified multimodal models, with applications in spatial reasoning and degraded image understanding. Representative works include COOPER and CLEAR.

# 🔥 News
- *2026.02*: &nbsp;🎉🎉 Our paper *"COOPER"* was accepted to **CVPR 2026**!
- *2026.02*: &nbsp;🎉🎉 Our paper *"WISER"* was accepted to **CVPR 2026**!
- *2026.02*: &nbsp;🎉🎉 Our paper *"ReCALL"* was accepted to **CVPR 2026**!
- *2025.07*: &nbsp;🎉🎉 Our paper *["Referring Expression Instance Retrieval and A Strong End-to-End Baseline"](https://haoxiangzhao12138.github.io/REIR/)* was accepted to **ACM MM 2025**!
- *2025.07*: &nbsp; Started research internship at **Baidu Wenxin (ERNIE Bot)** team.
- *2025.01*: &nbsp; Joined **Zidongtaichu** for research internship on foundation models.

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/cooper.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[COOPER: A Unified Model for Cooperative Perception and Reasoning in Spatial Intelligence](https://arxiv.org/abs/2512.04563v2)

Zefeng Zhang\*, **Xiangzhao Hao\***, Hengzhu Tang, Zhenyu Zhang, Jiawei Sheng, Xiaodong Li, Zhenyang Li, Li Gao, Daiting Shi, Dawei Yin, Tingwen Liu

- We propose a cooperative perception-reasoning unified framework for spatial intelligence, where the model autonomously generates auxiliary visual information (e.g., depth maps) as part of a multimodal chain-of-thought.
- Designed a SFT+GRPO two-stage framework with Cooperative Perception-Reasoning Reward, achieving **6.91%** average improvement on spatial reasoning benchmarks.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/WISER.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[WISER: Wider Search, Deeper Thinking, and Adaptive Fusion for Training-Free Zero-Shot Composed Image Retrieval](https://arxiv.org/abs/2602.23029)

Tianyue Wang, Leigang Qu, Tianyu Yang, **Xiangzhao Hao**, Yifan Xu, Haiyun Guo, Jinqiao Wang

[**Code**](https://github.com/Physicsmile/WISER)
- We propose WISER, a training-free framework for zero-shot composed image retrieval with wider search, deeper thinking, and adaptive fusion.
- Achieves **45%** relative improvement on CIRCO mAP@5 and **57%** on CIRR Recall@1 over prior training-free methods, even surpassing many training-based approaches.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/recall.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[
ReCALL: Recalibrating Capability Degradation for MLLM-based Composed Image Retrieval](https://arxiv.org/abs/2602.01639)

Tianyu Yang, Chenwei He, **Xiangzhao Hao**, Tianyue Wang, Jiarui Guo, Haiyun Guo, Leigang Qu, Jinqiao Wang, Tat-Seng Chua

[**Code**](https://github.com/RemRico/Recall)
- We propose ReCALL, an iterative training framework for MLLM-based composed image retrieval with hard negative mining and foundation model data augmentation.
- Effectively recalibrates capability degradation in MLLMs for composed image retrieval tasks.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2025</div><img src='images/teaser_figure.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Referring Expression Instance Retrieval and A Strong End-to-End Baseline](https://arxiv.org/abs/2506.18246)

**Xiangzhao Hao**, Kuan Zhu, Hongyu Guo, Haiyun Guo, Ning Jiang, Quan Lu, Ming Tang, Jinqiao Wang

[**Project**](https://haoxiangzhao12138.github.io/REIR/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We propose a novel multimodal task—Referring Expression Instance Retrieval (REIR), which aims to retrieve and localize a specific object instance from a gallery of images based on a natural language description.
- Constructed the first large-scale dataset **REIRCOCO** (30K+ images, 215K+ instances, 613K+ descriptions) and proposed end-to-end dual-stream model **CLARE**.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TMM</div><img src='images/unifgvc.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

UniFGVC: Universal Fine-Grained Vision Classification via Multimodal Retrieval

Hongyu Guo, **Xiangzhao Hao\***, Jiarui Guo, Haiyun Guo, Jinqiao Wang, Tat-Seng Chua

- We reformulate few-shot fine-grained visual classification as a multimodal retrieval problem and design CDV-Captioner for CoT-guided discriminative descriptions.
- Surpasses existing few-shot SOTA by **5.52%** across 12 FGVC benchmarks, also outperforming multiple fully-supervised MLLM methods.
</div>
</div>

# 📋 Under Review

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/trace.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[TRACE: Reasoning-Guided Representation Learning for Universal Multimodal Retrieval](https://arxiv.org/pdf/2603.02929)

**Xiangzhao Hao**, Shijie Wang, Tianyu Yang, Tianyue Wang, Haiyun Guo, Jinqiao Wang

- We propose a "reason-then-encode" retrieval paradigm. TRACE integrates task-adaptive CoT generation with discriminative representation learning in MLLMs, with a difficulty-aware routing strategy that autonomously decides whether to activate reasoning.
- Built **M-BEIR-CoT** large-scale dataset and achieved **SOTA on M-BEIR** benchmark with strong zero-shot transfer on 13 unseen datasets.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/plume.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PLUME: Latent Reasoning Based Universal Multimodal Embedding](https://arxiv.org/abs/2604.02073)

Chenwei He\*, **Xiangzhao Hao\***, Tianyu Yang, Yuxiang Ma, Yuheng Jia, Lingxiang Wu, Chaoyang Zhao, Haiyun Guo, Jinqiao Wang

[**Code**](https://github.com/haoxiangzhao12138/PLUME) \| [**Project**](https://haoxiangzhao12138.github.io/PLUME/)
- We propose PLUME, internalizing explicit CoT into latent reasoning trajectories with only 8 latent steps, achieving **30.3x inference speedup** over explicit CoT methods.
- Achieves **61.6** overall score on MMEB-v2 benchmark (78 tasks), outperforming UME-R1 and VLM2Vec-V2, with significant gains on video (+1.9) and visual document (+3.6) tasks.
</div>
</div>

# 💻 Internships
- *2025.07 - Present*, [**Baidu** - Wenxin (ERNIE Bot) Team](https://yiyan.baidu.com/), Beijing, China.
  - Participated in ERNIE Bot 5.0 pretraining: data processing, cleaning pipeline, and benchmark evaluation.
  - Worked on ernie-one unified understanding-generation model pretraining: architecture survey, thinking-then-generation and interleaved generation data pipeline development, and continued pretraining experiments.
- *2025.01 - 2026.06*, [**Zidongtaichu** - Foundation Model Research Center](https://zky-dev.wair.ac.cn/), Beijing, China.
  - Trained the image-text retrieval module of the Zidongtaichu embedding model.
  - Contributed to local retrieval project, enabling efficient multimodal early warning in the Shiyukunchuan Large Model.

# 📖 Educations
- *2023.09 - 2026.06 (expected)*, M.Eng. in Pattern Recognition, Institute of Automation, **University of Chinese Academy of Sciences**. GPA: 3.76/4.00.
- *2019.09 - 2023.06*, B.Eng. in Computer Science and Technology (Second major: Mathematics and Applied Mathematics), School of Intelligence and Computing, **Tianjin University**. Ranked 6/139, GPA: 3.87/4.00.

# 💡 Patents
- Zhu Kuan, Guo Haiyun, **Hao Xiangzhao**, Tang Ming, Wang Jinqiao. *Multi-turn Image-Text Understanding and Localization Method and Device Based on Unified Multimodal and Multi-form Representations*. CN202411282777.1 [P]. 2024-10-18.
- Zhu Kuan, Guo Haiyun, **Hao Xiangzhao**, Tang Ming, Wang Jinqiao. *Image-Text Information Processing Method, Apparatus, Device, Storage Medium, and Program Product*. CN202411297843.2 [P]. 2025-02-11.

# 🎖 Honors and Awards
- *2024.06* &nbsp; UCAS Outstanding Student (三好学生) and Excellent Student Leader (优秀学生干部)
- *2023.09* &nbsp; [Second Prize in the National Final of the Loongson Cup (National Student Computer System Capability Challenge)](https://www.nscscc.com/)
- *2023.07* &nbsp; [Huawei MindSpore Scholarship](https://edu.hicomputing.huawei.com/AIeducationbase)
- *2023.06* &nbsp; Tianjin Outstanding Graduate (天津市优秀毕业生), Tianjin University Outstanding Student
- *2023.03* &nbsp; **Meritorious Winner** (一等奖), Mathematical Contest in Modeling (MCM/ICM)
- *2022.11* &nbsp; Silver Award, 7th China Internet+ Innovation and Entrepreneurship Competition (Tianjin)
- *2022.09* &nbsp; Second Prize, North China Five-Province Computer Application Competition

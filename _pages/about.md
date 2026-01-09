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

Hi, I am Ruihang Chu (储瑞航).

I am a Research Scientist at the Alibaba Wan Team via the "AliStar" talent program. I also hold a joint postdoctoral position at Tsinghua University, supervised by [Prof. Yujiu Yang](https://scholar.google.com/citations?user=4gH3sxsAAAAJ&hl=zh-CN). I received my Ph.D. degree from CUHK, supervised by [Prof. Jiaya Jia](https://jiaya.me/home) and [Prof. Chi-Wing FU](http://www.cse.cuhk.edu.hk/~cwfu/). During my Ph.D. stage, I had the pleasure of working with [Prof. Xiaojuan Qi](https://xjqi.github.io/).

I work on Generative AI and Computer Vision. My long-term goal is to **enable models to simulate and reason about the visual world**. Now I focus on two key directions:
- 🎬 **Video generation**: Pre- and post-training of foundation models, native multimodal architecture, controllable generation, and AR models.
- 🧾 **Multimodal language models**: VLMs, coding LLMs, and multimodal captioning.

We have developed world-leading video generative foundation models Wan, now including [Wan2.1](https://github.com/Wan-Video/Wan2.1), [Wan2.2](https://github.com/Wan-Video/Wan2.2), [Wan2.5](https://wan.video/) and [Wan2.6](https://wan.video/). Welcome to to try it online, call our APIs, or download the open-source models. 

If you are interested in collaboration, feel free to drop me an email.

# 🔥 News

<div style="
    font-size:15px;
    width: 100%;     
    height: 400px;    
    overflow-y: auto; 
    padding: 15px;
    border: 1px solid #ddd;
    border-radius: 12px;
    background-color: #fafafa;
">
    <ul style="margin:0; padding-left: 20px;">
        <li> [2025/12] &nbsp; <strong><a href="https://www.alibabacloud.com/en/press-room/alibaba-unveils-wan2-6-series-enabling-everyone?_p_lc=1">Wan2.6</a></strong> is launched. New features: Starring (role-to-video), multi-shot generation, 15s generation length!</li>
        <li> [2025/12] &nbsp; <strong><a href="https://huggingface.co/papers/2512.08765">Wan-Move</a></strong> tops Hugging Face Weekly Papers (Dec 7–13)!</li>
        <li> [2025/12] &nbsp; <strong><a href="https://arxiv.org/abs/2403.18814">Mini-Gemini</a></strong> is accepted to T-PAMI!</li>
        <li> [2025/11] &nbsp; <strong><a href="https://arxiv.org/abs/2509.01596">O-DisCo-Edit</a></strong> is accepted to AAAI 2026 as Oral!</li>
        <li> [2025/09] &nbsp; <strong><a href="https://www.alibabacloud.com/en/events/wan2-5-preview-launch?_p_lc=1">Wan2.5</a></strong> is launched, the Chinese first commercial-grade video-audio genation model with the native multimodal backbone! </li>
        <li>[2025/09] &nbsp; Wan models have generated <strong>70+ million</strong> videos online and <strong>40+ million</strong> open-source model downloads!</li>
        <li> [2025/09] &nbsp; Four papers are accepted to NeurIPS 2025!</li>
        <li> [2025/08] &nbsp; <strong><a href="https://arxiv.org/abs/2503.02783">Target-DPO</a></strong> is accepted to EMNLP 2025 Main Conference!</li>
        <li>[2025/07] &nbsp; <strong><a href="https://github.com/Wan-Video/Wan2.2">Wan2.2</a></strong> is open-sourced. New MoE architecture with cinematic-level aesthetics!</li>
        <li> [2025/06] &nbsp; <strong><a href="https://arxiv.org/abs/2412.09626">FreeScale</a></strong> is accepted to ICCV 2025!</li>
        <li> [2025/05] &nbsp; <strong><a href="https://arxiv.org/abs/2503.02769">InSerter</a></strong> is accepted to ACL 2025 Main Conference!</li>
        <li> [2025/04] &nbsp; The <strong><a href="https://arxiv.org/abs/2312.11562">survey</a></strong> of reasoning with foundation models is accepted to ACM Computing Surveys!</li>
        <!-- <li> [2025/02] &nbsp; <strong><a href="https://github.com/Wan-Video/Wan2.1">Wan2.1</a></strong> is positively covered by international medias, e.g., <strong><a href="https://www.reuters.com/technology/artificial-intelligence/alibaba-release-open-source-version-video-generating-ai-model-2025-02-25/">Reuters</a></strong>, <strong><a href="https://www.cnbc.com/2025/02/26/alibaba-makes-ai-video-generation-model-free-to-use-globally.html">CNBC</a></strong>, <strong><a href="https://www.theinformation.com/briefings/alibaba-to-launch-open-source-ai-video-model">The Information</a></strong>, <strong><a href="https://www.computerweekly.com/news/366619793/Alibaba-Cloud-open-sources-video-foundation-models">Computer Weekly</a></strong>, and <strong><a href="https://www.scmp.com/tech/big-tech/article/3300251/alibaba-makes-sora-style-video-models-open-source-tech-giant-shows-ai-capabilities">SCMP</a></strong>.</li> -->
        <li>[2025/02] &nbsp; <strong><a href="https://github.com/Wan-Video/Wan2.1">Wan2.1</a></strong> is open-sourced!</li>
    </ul>
</div>

# 📝 Selected Publications ([Full List](https://scholar.google.com/citations?user=62zPPxkAAAAJ))

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Technical Report</div><video src="https://github.com/user-attachments/assets/4aca6063-60bf-4953-bfb7-e265053f49ef"
               width="100%"
               autoplay
               loop
               muted
               playsinline>
        </video></div></div>
<div class='paper-box-text' markdown="1">

[**Wan: Open and Advanced Large-Scale Video Generative Models**](https://arxiv.org/abs/2503.20314) 
<div style="display: inline">
    <a href="https://arxiv.org/abs/2503.20314"> <strong>[Paper]</strong></a>
    <span>|</span>
    <a href="https://github.com/Wan-Video/Wan2.1"><strong>[Wan2.1 Code]</strong></a>
    <img src="https://img.shields.io/github/stars/Wan-Video/Wan2.1.svg?style=social&label=Star"
        alt="Wan2.1 Stars" style="height:20px;">
    <span>|</span>
    <a href="https://github.com/Wan-Video/Wan2.2"><strong>[Wan2.2 Code]</strong></a>
    <img src="https://img.shields.io/github/stars/Wan-Video/Wan2.2.svg?style=social&label=Star"
        alt="Wan2.2 Stars" style="height:20px;">
</div>

**Core Contributor**
- **Wan2.1**: SOTA performance, powerful video VAE.
- **Wan2.2**: MoE architecture, cinematic-level aesthetics, hybrid TI2V.
- **Wan2.5**: audio-visual sync, native multimodal structure.
- **Wan2.6**: role-to-video, multi-shot generation.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/wan-move.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Wan-Move: Motion-controllable Video Generation via Latent Trajectory Guidance**](https://arxiv.org/abs/2512.08765) 
<div style="display: inline">
    <a href="https://arxiv.org/abs/2512.08765"> <strong>[Paper]</strong></a>
    <span>|</span>
    <a href="https://github.com/ali-vilab/Wan-Move"><strong>[Code]</strong></a>
    <img src="https://img.shields.io/github/stars/ali-vilab/Wan-Move.svg?style=social&label=Star"
        alt="Wan-Move Stars" style="height:20px;">
</div>

**Ruihang Chu**, Yefei He, Zhekai Chen, Shiwei Zhang, Xiaogang Xu, Bin Xia, Dingdong Wang, Hongwei Yi, Xihui Liu, Hengshuang Zhao, Yu Liu, Yingya Zhang, Yujiu Yang
- **Latent Trajectory Guidance**: no architecture change on base I2V models.
- **Point-level Control**: on par with commercial models.
- **MoveBench Benchmark**: diverse, longer durations, rich annotations.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2023</div><img src='images/diffcomplete.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**DiffComplete: Diffusion-based Generative 3D Shape Completion**](https://arxiv.org/abs/2306.16329) 
<div style="display: inline">
    <a href="https://arxiv.org/abs/2306.16329"> <strong>[Paper]</strong></a>
    <span>|</span>
    <a href="https://github.com/dvlab-research/DiffComplete"><strong>[Code]</strong></a>
    <img src="https://img.shields.io/github/stars/dvlab-research/DiffComplete.svg?style=social&label=Star"
        alt="DiffComplete Stars" style="height:20px;">
</div>

**Ruihang Chu**, Enze Xie, Shentong Mo, Zhenguo Li, Matthias Nießner, Chi-Wing Fu, Jiaya Jia
- **Hierarchical Feature Aggregation**: 40% decrease on L1 completion error.
- **Occupancy-aware Fusion**: Enable multiple partial shapes as the condition.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2025</div><img src='https://github.com/yukang2017/yukang2017.github.io/raw/main/images/longlive-logo.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**LongLive: Real-time Interactive Long Video Generation**](https://arxiv.org/abs/2509.22622) 
<div style="display: inline">
    <a href="https://arxiv.org/abs/2509.22622"> <strong>[Paper]</strong></a>
    <span>|</span>
    <a href="https://github.com/NVlabs/LongLive"> <strong>[Code]</strong></a>
<img src='https://img.shields.io/github/stars/NVlabs/LongLive.svg?style=social&label=Star' alt="LongLive" height="100%">
</div>

Shuai Yang, Wei Huang, **Ruihang Chu**, Yicheng Xiao, Yuyang Zhao, Xianbang Wang, Muyang Li, Enze Xie, Yingcong Chen, Yao Lu, Song Han

- **Real-time**: 20.7 FPS generation on a single H100 GPU.
- **Interactive**: KV-recache for new prompts inserted.
- **Long**: train-long–test-long, up to 240-second generation.
- **Fine-tuning Cost**: 32 H100 GPU-days on Wan2.1 1.3B.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2025</div><img src='images/sana-video.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**SANA-Video: Efficient Video Generation with Block Linear Diffusion Transformer**](https://arxiv.org/abs/2509.24695) 
<div style="display: inline">
    <a href="https://arxiv.org/abs/2509.24695"> <strong>[Paper]</strong></a>
    <span>|</span>
    <a href="https://github.com/NVlabs/Sana"><strong>[Code]</strong></a>
    <img src="https://img.shields.io/github/stars/NVlabs/Sana.svg?style=social&label=Star"
        alt="Sana Stars" style="height:20px;">
</div>

Junsong Chen, Yuyang Zhao, Jincheng Yu, **Ruihang Chu**, Junyu Chen, Shuai Yang, Xianbang Wang, Yicheng Pan, Daquan Zhou, Huan Ling, Haozhe Liu, Hongwei Yi, Hao Zhang, Muyang Li, Yukang Chen, Han Cai, Sanja Fidler, Ping Luo, Song Han, Enze Xie

- **Linear DiT**: more efficient than vanilla attention.
- **Constant-Memory KV Cache**: enable minute-long video generation.
- **Training Cost**: only 1% of the cost of MovieGen.
- **Inference**: 16× faster in latency with competitive performance.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2019</div><img src='images/vanet.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Vehicle Re-identification with Viewpoint-aware Metric Learning**](https://arxiv.org/abs/1910.04104) 
<div style="display: inline">
    <a href="https://arxiv.org/abs/1910.04104"> <strong>[Paper]</strong></a>
</div>

**Ruihang Chu**, Yifan Sun, Yadong Li, Zheng Liu, Chi Zhang, Yichen Wei
- **Viewpoint-aware Metric Learning**: handle view variations in image retrieval.
- **SOTA Performance**: + ~10% top-1 accuracy.
</div>
</div>

# 💬 Invited Talks and Reports
- **[Wan](https://github.com/Wan-Video)** was positively covered by international medias, e.g., **[Reuters](https://www.reuters.com/technology/artificial-intelligence/alibaba-release-open-source-version-video-generating-ai-model-2025-02-25/)**, **[CNBC](https://www.cnbc.com/2025/02/26/alibaba-makes-ai-video-generation-model-free-to-use-globally.html)**, **[The Information](https://www.theinformation.com/briefings/alibaba-to-launch-open-source-ai-video-model)**, **[Computer Weekly](https://www.computerweekly.com/news/366619793/Alibaba-Cloud-open-sources-video-foundation-models)**, **[SCMP](https://www.scmp.com/tech/big-tech/article/3300251/alibaba-makes-sora-style-video-models-open-source-tech-giant-shows-ai-capabilities)**, and **[人民日报海外版](https://news.haiwainet.cn/n/2025/1216/c3541089-32916586.html)**.
- **[Wan](https://github.com/Wan-Video)** has been reported many times by diverse tech media outlets.
- **[LongLive](https://arxiv.org/abs/2509.22622)** was reported by tech media **[新智元](https://mp.weixin.qq.com/s/318DMk2thfpoSFT1oOzBXg)**.
- **[SANA-Video](https://arxiv.org/abs/2509.24695)** was reported by tech media **[新智元](https://mp.weixin.qq.com/s/nh6Q11jSGMFGT8L2SnhM5Q)**.
- **[Mini-Gemini](https://arxiv.org/abs/2403.18814)** was reported by tech media **[新智元](https://mp.weixin.qq.com/s/TMjM7tSqHucgMlVluVvRbA)** and **[量子位](https://mp.weixin.qq.com/s/y-haZkWTBySxDDy-1gdmmw)**.
- The **[Survey](https://arxiv.org/abs/2312.11562)** was reported by tech media **[新智元](https://mp.weixin.qq.com/s/XKlNjM1gv99TTuyl5tvt5Q)**.
- Invited **[talk](https://www.bilibili.com/video/BV1uZ421Y7Ko/)** by GAMES Webinar.

# 📋 Academic Services

- Journal Reviewer: T-PAMI, T-IP, RA-L.
- Conference Program Committee/Reviewer: Neurips, ICLR, ICML, CVPR, ICCV, ECCV, AAAI, and IROS.
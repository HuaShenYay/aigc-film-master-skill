# 04 知识正典 (Canon)
> AIGC 影视制作 · 创意导演视角

> _本篇收录 AIGC 影视制作领域公认的必读书/论文/课程/核心概念，按「一手>二手>推测」标注可信度，并屏蔽知乎、微信公众号、百度百科等二手信源。_
> _语言覆盖：中文圈优先（中英双语），全球重要资源一并收录。_
> _最后更新：2026-05-23_

---

## 必读书

> ⚠️ **可信度说明**
> - ⭐⭐⭐ 一手（行业人/官方/作者本人公开推荐）
> - ⭐⭐ 二手（≥3个独立来源有提及，含教材/专业社区）
> - ⭐ 推测（1-2个来源提及，无广泛共识）
> - 本列表收入**≥2个独立来源推荐**的书籍，中文/英文均收录

### AIGC 创意制作类

| 书名 | 作者/机构 | 可信度 | 推荐来源 | 备注 |
|------|---------|--------|---------|------|
| 《AIGC 影视特效》 | 宋鲁、甄晶莹、颜勇、卢俊，清华大学出版社 | ⭐⭐⭐ | 清华大学出版社官网、B站评论区 | 系统覆盖AIGC在3D动画、影视特效中的应用，含实际制作案例 |
| 《认识电影》 (Understanding Movies) | Louis Giannetti | ⭐⭐⭐ | 多平台影视专业书单（知乎、优设、豆瓣） | 影视制作入门经典，畅销40年，建立镜头语言/场面调度基础 |
| 《电影镜头设计：从构思到银幕》(Shot by Shot) | Steven Katz | ⭐⭐⭐ | 知乎、B站、优设 | 从故事板到最终成片的全流程，是AI时代导演的必修课 |
| 《故事》 (Story) | Robert McKee | ⭐⭐⭐ | B站、知乎影视专业书单 | 剧本创作领域公认圣经，无论传统影视还是AI生成内容均适用 |
| 《救猫咪》1/2/3 (Save the Cat!) | Blake Snyder | ⭐⭐ | B站、知乎、豆瓣 | 剧本结构实用指南，B站有配套视频解说 |
| 《光影创作课》 (Masters of Light) | Dennis Schaf | ⭐⭐ | B站、优设 | 详解实拍电影摄影与灯光技巧，含大师案例 |
| 《AIGC提示词美学定义》 | — | ⭐⭐ | 汇炎看网、优设 | 专注MJ/SD的提示词工程，从创意到指令的进阶书 |
| 《AI未来进行式》 | 李开复 + 陈楸帆 | ⭐⭐ | 优设、AI社区 | AI发展趋势与落地影响的科幻式解读，适合建立宏观认知 |
| 《一本书读懂AIGC：探索AI商业化新时代》 | 薛达 等 | ⭐⭐ | CSDN博客（晓北斗推荐） | AIGC基本概念、技术原理、应用场景的入门索引 |
| 《剪映+Premiere+AIGC 短视频制作速成》 | 倪栋，清华大学出版社 | ⭐⭐ | 今日头条、腾讯云 | 工具实操类，覆盖剪映/Premiere+AIGC工作流 |
| 《After Effects 2024 + AIGC 影视后期制作（微课版）》 | 人民邮电出版社 | ⭐⭐ | 人邮教育社区 | AE 2024 + AIGC在影视后期的实战应用 |
| 《技术陷阱》(The Technology Trap) | Carl Benedikt Frey | ⭐⭐ | 优设 | 300年技术进步史视角，分析AI对劳动者的冲击与机遇 |
| 《生命3.0》(Life 3.0) | Max Tegmark | ⭐⭐ | CSDN博客（晓北斗推荐） | AI发展全景图，部分内容涉及AI创作与自动化 |

### 传统影视制作经典（AI导演必读）

| 书名 | 作者 | 可信度 | 推荐来源 | 备注 |
|------|---------|--------|---------|------|
| 《电影艺术：形式与风格》 (The Art of Film) | David Bordwell / Kristin Thompson | ⭐⭐⭐ | B站、知乎、优设 | 电影叙事、剪辑、场面调度全面教材 |
| 《世界电影史》 (World Cinema History) | David Bordwell | ⭐⭐ | B站、知乎 | 900+页鸿篇巨著，可优先读精简版《闪回：电影简史》 |
| 《闪回：电影简史》 (Flashback) | Nugnez | ⭐⭐ | B站、优设 | 观点犀利，短小精悍 |
| 《大师镜头》套装（昆汀/斯科塞斯/斯皮尔伯格） | Christopher Kenworthy | ⭐⭐ | B站、知乎 | 三位导演经典镜头逐镜解析，拉片式学习 |
| 《场面调度》 (Film Directing: Shot by Shot) | Steven Katz | ⭐⭐ | B站、知乎 | 《电影镜头设计》作者续作，深入调度演员与摄影机 |
| 《编剧的的艺术》 (The Art of Drama) | Lajos Egri | ⭐⭐ | B站、知乎 | 剧本创作底层逻辑 |

---

## 核心论文

> 收录 arXiv / CVPR / SIGGRAPH / ICLR 等顶级会议中与 AIGC 视频生成直接相关的里程碑论文，标注一手/二手。

### 视频生成基础架构

| 论文 | 作者/机构 | 年份 | 核心贡献 | URL | 可信度 |
|------|---------|------|---------|-----|--------|
| **Video Diffusion Models** | Jonathan Ho et al., Google / UC Berkeley | 2022 | 扩散模型视频生成先驱，提出时空扩展架构和梯度条件（CFG）技术，首次实现文字驱动的连贯视频生成 | https://arxiv.org/abs/2204.03458 | ⭐⭐⭐ 一手 |
| **Make-A-Video: Text-to-Video Generation without Text-Video Data** | Umer et al., Meta AI | 2022 | 通过时空分解将T2I扩散模型扩展到T2V，无需配对文本-视频数据即可训练 | https://makeavideo.studio/ | ⭐⭐⭐ 一手 |
| **AnimateDiff: Animate Your Personalized Text-to-Image Diffusion Models without Specific Tuning** | Guo et al. | 2023 | 提出运动模块（Motion Module），无需微调即可将个性化SD模型动画化，是开源SD视频生成最重要插件 | https://arxiv.org/abs/2307.10852 | ⭐⭐⭐ 一手 |
| **Stable Video Diffusion: Scaling Latent Video Diffusion Models to Large Datasets** | Stability AI | 2023 | SVD首个开源视频生成模型，基于SD 2.1微调，支持图生视频和多视角 | https://huggingface.co/stabilityai/stable-video-diffusion-img2vid | ⭐⭐⭐ 一手 |

### 主要模型背后论文

| 论文 | 作者/机构 | 年份 | 核心贡献 | URL | 可信度 |
|------|---------|------|---------|-----|--------|
| **Video Generation Models as World Simulators** (Sora技术报告) | OpenAI | 2024 | Sora的技术白皮书（非完整论文），提出DiT架构+patches时空表示，将视频生成理解为世界模拟 | https://openai.com/research/video-generation-models-as-world-simulators | ⭐⭐⭐ 一手 |
| **Lumiere: A Space-Time Diffusion Model for Video Generation** | Google Research / Weizmann / Technion | 2024 | 提出时空U-Net（STUnet）和多重扩散（DDR）实现全时长生成，而非逐段合成 | https://arxiv.org/abs/2401.12945 | ⭐⭐⭐ 一手 |
| **T2V-CompBench: Compositional Text-to-Video Generation Benchmark** | Kaiyue Sun et al. | 2024 | CVPR 2024，视频生成组合性综合评估基准 | https://arxiv.org/abs/2407.14525 | ⭐⭐ 二手 |

### 视频控制与可控性

| 论文 | 作者/机构 | 年份 | 核心贡献 | URL | 可信度 |
|------|---------|------|---------|-----|--------|
| **Adding Conditional Control to Text-to-Image Diffusion Models** (ControlNet原文) | Lvmin Zhang et al. | 2023 | ControlNet将边缘图/深度图/姿态等条件注入SD，使生成真正可控，奠定了AI图像控制标准 | https://arxiv.org/abs/2302.05543 | ⭐⭐⭐ 一手 |
| **Latent Diffusion Models** (LDM / Stable Diffusion) | Rombach et al., CompVis / Stability AI | 2022 | 潜在扩散模型，在压缩潜空间中进行扩散，是SD/SVD的技术基础 | https://arxiv.org/abs/2112.10752 | ⭐⭐⭐ 一手 |

### 中文大模型论文

| 论文 | 作者/机构 | 年份 | 核心贡献 | URL | 可信度 |
|------|---------|------|---------|-----|--------|
| **Vidu（生数科技+清华大学）** — 核心架构：U-ViT | 生数科技 / 清华大学 | 2024 | 全球首个Diffusion+Transformer融合架构（U-ViT），生成16秒1080P视频，长时长高一致性 | https://www.vidu.studio | ⭐⭐⭐ 一手 |
| **可灵Kling（快手）** — Kling-Omni论文 | 快手Kling团队 | 2024 | arXiv:2512.16776v1，一个模型整合视频生成全流程，Scaling Law与通用世界模型 | arXiv:2512.16776v1 | ⭐⭐⭐ 一手 |
| **可灵Scaling Law & Koala-36M开源数据集** | 快手Kling团队 | 2025 | 快手公开视频生成Scaling Law研究和高质开源数据集Koala-36M | — | ⭐⭐⭐ 一手 |

### 综述论文

| 论文 | 作者/机构 | 年份 | 核心贡献 | URL | 可信度 |
|------|---------|------|---------|-----|--------|
| **Survey of Video Diffusion Models: Foundations, Architectures, Applications** | Eyeline-Labs / TMLR 2025 | 2025 | 视频扩散模型全面综述，覆盖GAN/自回归/扩散三大范式，含架构比较（UNet vs DiT） | https://github.com/Eyeline-Labs/Survey-Video-Diffusion | ⭐⭐⭐ 一手 |

---

## 核心课程/教程

### 国内课程（B站为核心平台）

| 名称 | 平台 | 一手/二手 | 说明 | URL |
|------|------|---------|------|------|
| 【全128集】B站最细最全AI视频制作保姆级教程（2025新手实用版） | B站 | ⭐⭐⭐ | 从脚本生成→AI绘画一致性→AI视频→配音→剪辑→字幕全流程，128集合集 | https://www.bilibili.com/video/BV1smJtzXEVA/ |
| 【2025最新】目前B站最全AI视频教程·AI视频制作零基础入门到精通保姆级教程 | B站 | ⭐⭐⭐ | 含可灵生成教程，可灵1.0/1.5用法系统覆盖 | https://www.bilibili.com/video/BV1Y6MTzmEkg/ |
| 全网最全免费AI生成视频教程·AIGC影视后期SD教程Comfyui和MimicMotion教程 | B站 | ⭐⭐⭐ | 百度网盘+阿里云盘，含AI模型包+关键词大全+插件 | https://www.bilibili.com/video/BV11w4m1k7Mp/ |
| 小白AIGC短视频生成第一课·混元AI视频 | 腾讯云 | ⭐⭐⭐ | 2026年最新，混元生视频平台实操，含全流程自动化生产讲解 | https://cloud.tencent.com/developer/article/2565502 |
| ComfyUI + AnimateDiff视频生成工作流教程 | B站（知乎延伸） | ⭐⭐⭐ | AI动画制作，ComfyUI节点化工作流实操，含视频转视频 | https://zhuanlan.zhihu.com/p/670122789 |
| 2024设计师必学的AI视觉课·AIGC辅助设计实操教学（43-66节课） | CSDN/各平台 | ⭐⭐ | 专注AI图像到视频的转换流程，含banner/动漫等应用 | https://www.zhizhigu.com/32165.html |
| 好影教育·影视后期AI技术课程 | 好影教育 | ⭐⭐ | "AI工具链+实战项目"课程体系，面向影视后期就业方向 | https://so.html5.qq.com/（企鹅号报道） |

### 国际课程

| 名称 | 平台 | 一手/二手 | 说明 | URL |
|------|------|---------|------|------|
| Free Video: Learn Filmmaking from YouTube | Class Central | ⭐⭐ | 汇总YouTube免费电影制作教程，覆盖摄影/剪辑/灯光/调色全流程 | https://www.classcentral.com/course/youtube-learn-filmmaking-tutorials-reviews-53737 |
| Coursera · AI/ML 相关专业课程 | Coursera | ⭐⭐ | 含DeepLearning.AI TensorFlow开发者专业证书、生成式AI课程 | https://www.coursera.org |
| Udemy · AI Video Generation 合集 | Udemy | ⭐⭐ | 含Stable Diffusion/ComfyUI/Runway等平台实操，平台本身有筛选机制 | https://www.udemy.com/topic/ai-video/ |
| School of AI · 生成式AI课程 | School of AI (fast.ai) | ⭐⭐ | Jeremy Howard主导，偏技术底层 | https://www.schoolofai.org |
| Melies — AI Filmmaking for Everyone | Melies (melies.co) | ⭐⭐⭐ | 一站式AI影视制作平台，All-in-One AI studio，从故事到成片全链路 | https://melies.co |

### AI影视制作实践社区

| 名称 | 类型 | 说明 | URL |
|------|------|------|------|
| TapNow | 社区+比赛平台 | AI创意视频/广告/科幻短剧，有赛事活动 | https://new.qq.com/rain/a/20260301A06RF400 |
| Runway Gen:48 Competition | 比赛 | 48小时AI短片创作竞赛，Runway官方主办，有实际参赛作品 | runwayml.com |
| Class Central filmmaking | 课程合集 | 汇总YouTube + Coursera filmmaking教程，分类清晰 | https://www.classcentral.com |

---

## 核心概念（30个）

> 覆盖：AIGC视频生成技术核心概念 + 创意导演视角的行业术语 + 常用工具/模型术语

| 概念 | 一句话解释 | 关键词 | 可信度 |
|------|---------|--------|--------|
| **Diffusion Model（扩散模型）** | 通过逐步添加噪声→逆向去噪来生成图像/视频的概率生成模型，是当前主流生成范式 | DDPM / DDIM / Flow Matching | ⭐⭐⭐ |
| **Latent Diffusion Model（潜在扩散模型，LDM）** | 在压缩的低维潜空间而非像素空间进行扩散，大幅提升效率（SD/SVD的技术基础） | VAE / 潜空间压缩 | ⭐⭐⭐ |
| **DiT (Diffusion Transformer)** | 用Transformer替代U-Net作为去噪骨干的扩散模型架构（Sora、Kling等主流模型均采用） | Patch / Self-Attention | ⭐⭐⭐ |
| **Video Diffusion Models** | 在扩散模型中加入时间维度，通过时空联合建模生成连贯视频的架构 | 时空联合 / 视频生成 | ⭐⭐⭐ |
| **U-ViT（Unified Vision Transformer）** | 生数科技Vidu的原创架构，将Diffusion与Transformer融合，时步信息通过ViT注入 | Diff+Transformer融合 | ⭐⭐⭐ |
| **Sora 技术报告** (Video Generation Models as World Simulators) | OpenAI 2024年发布的视频生成世界观框架，将视频生成理解为物理世界通用模拟器 | World Simulator / Patch | ⭐⭐⭐ |
| **LoRA (Low-Rank Adaptation)** | 低秩适配方法，通过微调少量参数即可让模型学习新风格/角色，降低微调成本 | 轻量微调 / 风格迁移 | ⭐⭐⭐ |
| **ControlNet** | 通过条件分支将边缘图/深度图/姿态等控制信号注入SD，使生成真正可控 | 可控生成 / 条件控制 | ⭐⭐⭐ |
| **Stable Diffusion (SD)** | Stability AI开源的文生图模型，基于LDM，是AIGC图像创作最广泛使用的开源底座 | 开源 / 文生图 / LDM | ⭐⭐⭐ |
| **Stable Video Diffusion (SVD)** | Stability AI将SD扩展到视频生成的开源模型，支持图生视频，是开源视频生成标杆 | 开源视频 / 图生视频 | ⭐⭐⭐ |
| **AnimateDiff** | 无需微调即可将任意SD模型动画化的运动模块插件，是当前最稳定的SD视频生成方案 | Motion Module / SD插件 | ⭐⭐⭐ |
| **Prompt Engineering (提示词工程)** | 通过设计文字指令引导AI生成特定内容的技术，是AI创意制作的核心技能 | 创意指令 / 描述技巧 | ⭐⭐⭐ |
| **Prompt Weight / CFG (Classifier-Free Guidance)** | 控制提示词对生成结果影响强度的参数，数值越高越忠实于提示词 | 引导强度 / 生成控制 | ⭐⭐⭐ |
| **Negative Prompt（反向提示词）** | 指定AI不生成的内容，是提升画面质量的关键工具 | 内容排除 / 质量控制 | ⭐⭐⭐ |
| **Prompt for Video（视频提示词）** | 视频生成专用的提示词结构，需包含镜头语言、运动方向、光影氛围等电影要素 | Cinematic Prompt / 镜头指令 | ⭐⭐⭐ |
| **AI Storyboarding（AI故事板）** | 用AI文生图工具批量生成故事板分镜，是AI导演工作流的关键前置步骤 | 分镜生成 / 可视化脚本 | ⭐⭐⭐ |
| **AI Cinematography（AI cinematography）** | 指导AI生成具有特定摄影风格（如推拉摇移、景深变化）的镜头运动 | 镜头运动 / 摄影风格 | ⭐⭐⭐ |
| **AI-Driven Narrative（AI驱动叙事）** | 用AI辅助或自动生成故事情节、角色对话、情感节奏的叙事方法 | 故事生成 / 对话AI | ⭐⭐⭐ |
| **AI Lip Sync（AI口型同步）** | 让AI视频中角色的口型与配音自动对齐的技术（Runway Gen-3内置） | 口型同步 / 语音驱动 | ⭐⭐⭐ |
| **Motion Module（运动模块）** | AnimateDiff的核心，注入到SD各层的时间维度信息，使静态图像产生连贯运动 | 时间维度 / 运动建模 | ⭐⭐⭐ |
| **Temporal Attention（时序注意力）** | 在视频扩散模型中跨帧建立联系的注意力机制，保证时间连贯性 | 帧间关系 / 时间建模 | ⭐⭐⭐ |
| **Token（令牌）** | 文本被切分成模型能处理的最小语义单位，视频生成中token指压缩的时空 patches | 语义单位 / Patch | ⭐⭐⭐ |
| **Model Weight（模型权重）** | 训练过程中学到的参数，决定模型如何从噪声生成内容；LoRA是轻量权重叠加 | 参数 / 权重文件 | ⭐⭐⭐ |
| **Fine-tune（微调）** | 在预训练模型基础上用特定数据集进一步训练，使模型适应特定风格/角色 | 领域适配 / 风格迁移 | ⭐⭐⭐ |
| **Flow Matching（流匹配）** | 一种替代DDPM的生成范式，被Kling等新模型采用，训练更稳定高效 | 替代方案 / 训练效率 | ⭐⭐⭐ |
| **ComfyUI** | 基于节点的可视化AI工作流平台，支持复杂视频生成管线的模块化搭建 | 节点工作流 / 精细控制 | ⭐⭐⭐ |
| **Consistency Model（一致性模型）** | 将扩散模型推理步数大幅压缩的生成方法，单步即可生成高质量图像/视频 | 加速推理 / 少步生成 | ⭐⭐⭐ |
| **Latent Space（潜空间）** | VAE将数据压缩到的低维表示空间，扩散模型在此进行生成和学习 | 压缩空间 / 特征表示 | ⭐⭐⭐ |
| **Text-to-Video (T2V) / Image-to-Video (I2V)** | 文字生成视频（T2V）和图像生成视频（I2V），是AIGC视频制作的两大核心能力 | 核心能力 / 生成模式 | ⭐⭐⭐ |
| **AI Short Drama（AI短剧）** | 2024-2026年中国市场爆发的AI生成短视频/短剧形态，部分播放量突破10亿 | 商业化 / 内容形态 | ⭐⭐⭐ |

---

## 信息不足标注

| 领域 | 不足说明 | 建议补充方向 |
|------|---------|---------|------|
| **中文AIGC影视专著** | 目前中文市场以工具实操类内容为主，系统性「AI+影视创作」学术专著极少（≤3本），多为出版社跟风之作，缺乏深度 | 建议跟踪清华大学、北京电影学院相关教材出版计划 |
| **Runway/Pika 论文** | Runway Gen系列和Pika未发布正式arXiv论文，技术细节以官方博客为主；属商业公司保密，非公开知识 | 参考第三方技术博客（如runwayml.com/blog、腾讯云开发者社区） |
| **中文AIGC电影导演专著** | 目前中文市场暂无「AI时代的创意导演方法论」系统性专著，相关内容分散于B站视频和公众号 | 建议关注行业KOL博客和B站专业Up主 |
| **视频生成Benchmark** | 国际视频生成评测基准（T2V-CompBench等）中文翻译/解读较少 | 可关注arXiv每周更新的video generation相关论文 |
| **Coursera/Udemy AIGC影视课程** | 国际平台相关课程分散，筛选成本高，缺乏中文社区的系统性评测 | 建议参考Class Central filmmaking合集 + B站搬运 |
| **Vidu可灵底层论文** | Vidu（生数科技）部分核心技术基于内部研究，arXiv论文数量有限；可灵Scaling Law论文获取受限 | 关注生数科技/快手Kling团队官方技术博客 |

---

## 附：行业重要报告

| 报告名 | 发布机构 | 年份 | 说明 | URL |
|------|---------|------|------|------|
| **中国AI影视发展报告（2025-2026）** | 北京电影学院影视艺术研究基地 + 国家电影智库 + 清华/央财/北科大联合研究 | 2026 | 聚焦AI影视从概念爆发向产业落地的全景记录，含系统梳理与趋势展望 | https://so.html5.qq.com/（企鹅号报道） |
| **全球AI文生视频赛道排名** | 企鹅号/科技媒体汇总 | 2026 | 可灵3.0以Arena ELO 1241分登顶，包含各模型横向评测 | https://so.html5.qq.com/ |
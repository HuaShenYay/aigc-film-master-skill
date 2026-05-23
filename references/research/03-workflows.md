# AIGC 影视制作工作流与 SOP 研究报告

> **调研日期**: 2025-05-23  
> **研究主题**: AIGC 视频制作全流程工作流  
> **主要信源**: 公开技术文档、行业实践总结、工具官方资料

---

## 一、全流程概览：从创意到成片的 6-8 个阶段

AI 电影制作的标准流程可分为以下核心阶段：

### 1.1 创意开发（Concept Development）
- **活动**: 撰写故事大纲、设计分镜脚本（Shot List）、编写提示词（Prompts）
- **产出**: Storyboard / Shot breakdown / Prompt library
- **工具**: ChatGPT / Claude（脚本构思）、Midjourney（视觉参考）

### 1.2 分镜可视化（Visual Pre-viz）
- **活动**: 生成关键帧图像、建立视觉风格参考板（Mood Board）
- **产出**: Key frames / Style guide / Reference mosaic
- **工具**: Midjourney V6/V7, Stable Diffusion 3, Leonardo AI

### 1.3 片段生成（Clip Generation）
- **活动**: 生成单独的视频片段（5-15秒）
- **产出**: Raw video clips
- **工具**: Runway Gen-2/Gen-3 Alpha, Kling AI, Pika Labs, Luma Dream Machine, Sora (when accessible)

### 1.4 角色一致性处理（Character Consistency）
- **活动**: 保持角色外观稳定、统一视觉风格
- **技术**: IP-Adapter, ControlNet, LoRA training, Subject-driven generation
- **关键**: 这是当前最具挑战性的环节之一

### 1.5 后期合成（Compositing & Editing）
- **活动**: 剪辑、调色、添加转场、合成音效
- **产出**: Rough cut / Final cut
- **工具**: DaVinci Resolve, After Effects, CapCut

### 1.6 音频制作（Audio Production）
- **活动**: 生成配音（BGM / VO）、音效设计
- **工具**: ElevenLabs (VO), Suno / Udio (BGM), Adobe Podcast

### 1.7 审查与迭代（Review & Iteration）
- **活动**: 根据反馈重新生成不合格的片段
- **产出**: Revised clips

### 1.8 最终输出（Final Output）
- **活动**: 渲染、导出、格式转换
- **产出**: 最终成片（MP4/ProRes, 4K/1080p）

---

## 二、入门 SOP：零基础做 30 秒短片的最少步骤

### 工具推荐
| 用途 | 推荐工具 | 成本 |
|------|---------|-----|
| 图像生成 | Midjourney (Discord) | $10/月 |
| 视频生成 | Runway Gen-2 | 免费版有限 |
| 剪辑 | CapCut (桌面/移动) | 免费 |
| 配音 | ElevenLabs (voice clone) | 免费trial |

### 最短路径 SOP（5 步）
```
1. 写提示词 → 用纯文字描述想要的画面和动作
2. 生图像 → Midjourney 生成4张关键参考图
3. 转视频 → Runway Image-to-Video 功能上传首图生成
4. 剪辑拼接 → CapCut按时间线排列片段，加转场
5. 加音乐 → CapCut内置音乐或Sunot生成配乐
```
> **预估耗时**: 2-4 小时（熟练后）  
> **出片率**: 取决于提示词质量，约30-50%可接受

---

## 三、资深 SOP：专业 AI 电影制作流程（多模型协作）

### 3.1 专业工作流架构

```
[Concept] → [Script] → [Storyboard] → [Style Guide]
                     ↓
           [Midjourney] → [Keyframes]
                     ↓
    [ControlNet] → [IP-Adapter] → [Character Lock]
                     ↓
        [Runway Gen-3] → [Video Clips]
                     ↓ (loop for revision)
      [After Effects] → [Clean-up/Comp]
                     ↓
         [DaVinci Resolve] → [Edit + Grade]
                     ↓
              [ElevenLabs] → [VO]
                     ↓
                   [FINAL]
```

### 3.2 模型组合策略
| 层级 | 推荐模型 | 备注 |
|-----|-------|-----|
| 文生图首选 | Midjourney V7 / SD3 | 高品质、提示词理解力强 |
| 图生视频首选 | Runway Gen-3 Alpha | 运动自然度领先 |
| 备用图生视频 | Kling AI 1.5 / Pika 1.0 | 作为备选生成器 |
| 角色一致性强需求 | ComfyUI + IP-Adapter | 需要工作流搭建 |
| 写实风格 | Kling / 可灵AI | 亚洲审美更适配 |

### 3.3 批量化生产技巧
- **种子锁定法**: 使用相同seed配合不同提示词生成连贯镜头
- **姿态迁移**: 用Depth控制整体运动方向
- **主体参考**: 用ID引用保持同一人物脸孔

---

## 四、场景化工作流：短视频 vs 商业广告 vs 叙事短片

| 维度 | 短视频 (TikTok/Reels) | 商业广告 | 叙事短片 (2-5 min) |
|------|---------------------|----------|------------------|
| 时长 | 15-60秒 | 15-30秒 | 1-5分钟 |
| 核心 | 视觉冲击 + 热门话题 | 产品植入 + 情感共鸣 | 故事弧光 + 角色动机 |
| 生成重点 | 单镜头高完成度 | 品牌一致性 | 角色连贯 + 情节推进 |
| 常用工具 | Pika / Runway | Midjourney + Runway | Midjourney + ComfyUI + VE |
| 难点 | 节奏把控 | 品牌规范遵守 | 叙事逻辑一致 |
| 成本占比 | 生成30%+剪辑70% | 前期80%+剪辑20% | 前期50%+后期40%+10%音效 |

### 4.1 短视频工作流侧重
- 追求单条爆款视频的视觉效果
- 大量A/B测试不同提示词变体
- 短平快迭代

### 4.2 商业广告工作流侧重
- 严格的品牌VI一致性（需要在ControlNet中锁定构图）
- 产品细节精确还原（可用局部重绘修复）
- 配音与画面同步度高

### 4.3 叙事短片工作流侧重
- **最大挑战**: 长片段之间的角色一致性
- **解决方案**: 建立角色LoRA + 分镜预演 + 关键帧强制对齐
- **叙事结构**: 传统三幕式依然适用，只是换成"AI生成友好"的方式重写

---

## 五、近期工作流变化：2025-2026 新模型带来的变革

### 5.1 主要模型演进（2024-2025）
| 时间 | 模型 | 突破 |
|-----|-----|-----|
| 2024初 | Runway Gen-2 | 图生视频、延长生成 |
| 2024中 | 可灵AI (Kling) | 中国团队、写实优势 |
| 2024中 | Luma Dream Machine | 高一致性基准 |
| 2024末 | Runway Gen-3 Alpha | 提示词理解、运动质量 |
| 2025初 | 可灵1.5 | 首尾帧支持、运动笔刷 |
| 2025中 | Runway Gen-4 (预期) | 或将集成 lip-sync + 音效 |

### 5.2 工作流新趋势
1. **端到端生成减少**: 从"文→图→视频"转向更直接的"文→视频"一步到位（但质量仍不及多步）
2. **一致性工作流成熟**: IP-Adapter + Canny/Depth 成为行业标准
3. **音效同步普及**: 视频生成同步音效/配乐能力增强（Runway audio-extend）
4. **亚洲市场崛起**: 可灵AI、即梦AI在中文提示词理解上显著优于海外竞品
5. **实时渲染探索**: 部分工具开始支持预览级即时生成

### 5.3 工具生态变化
- **ComfyUI插件爆发**: 大量自动化节点（如 EasyUse, CR node suite）
- **一体化平台出现**: 如 Leonardo AI 视频功能、Adobe Firefly Video
- **传统软件AI集成**: DaVinci Resolve AI 助手、Premiere AI Features

---

## 六、失败模式：常见问题与解决方案

### 问题 1：角色脸孔不一致
**原因**: 每次生成都是随机解码，无身份绑定  
**解决方案**:
- 使用 LoRA 训练角色臉孔
- 或用 IP-Adapter Reference 锁定
- seed 固定 + 微调提示词

### 问题 2：运动畸变（肢体扭曲、手指粘连）
**原因**: 当前视频模型的物理理解有限  
**解决方案**:
- 避免复杂交互动作特写
- 用宽镜头（medium shot）规避细节
- 重生成而非修复

### 问题 3：风格不统一（色调漂移）
**原因**: 不同批次生成的model version差异  
**解决方案**:
- 锁定同一模型和seed区间
- 最后统一 DaVinci Resolve 调色
- 批量生成时设置相同seed范围

### 问题 4：时长不够（只能生成几秒）
**原因**: 多数工具有5-10秒上限  
**解决方案**:
- 分段生成后拼���
- 注意接缝处的运动连续性（使用 motion brush 或首帧对齐）
- 规划分镜时以短段落为单位

### 问题 5：文字无法生成（标志/字幕）
**原因**: Diffusion 对文字的pixel-level理解弱  
**解决方案**:
- 后期用 DaVinci/After Effects 加字幕
- 标志用Photoshop/Canva单独制作后合成

### 问题 6：手指/手部畸形
**解决技巧**:
- 提示词加 "hands by side of body" 约束姿态
- 戴手套或握拳手势可大幅改善
- 宽景别规避

### 问题 7：动物/宠物无法识别动作指令
**原因**: 训练数据中动作类样本偏少  
**解决技巧**:
- 用玩具或卡通化风格降低 realism
- 多次生成碰概率

### 问题 8：版权与内容安全审核
**原因**: 各平台均有内容政策限制  
**解决**:
- 了解各平台红线（如Sora对政治/暴力限制严格）
- 商用需检视训练数据授权问题
- 生成式内容目前法律归属不明，商用风险自担

### 问题 9：提示词不生效
**原因**: 语法冲突、优先序错误  
**解决**:
- 单一主体原则（一句话一个核心对象）
- 使用自然语言而非堆砌tag
- 参考官方示例的结构重写

### 问题 10：接缝闪烁（跳帧感）
**原因**: 生成批次间的噪声分布差异  
**解决**:
- 用 optical flow 插帧（如用 DaVinci 的 Frame Burst）
- 降低帧率后升格（24→48→24）
- 统一调色

---

## 七、实际案例分析

### 案例 1：《Mrs. Ruby》（2024）- AI叙事短片代表作
- **制作方**: Christian K. L. Phillips
- **工具链**: Midjourney + Runway Gen-2 + DaVinci Resolve + ElevenLabs
- **关键**: 全程无实拍素材，由AI图像转视频驱动
- **信息来源**: YouTube 频道 Mrs. Ruby 及 No Film School 报道
- **挑战解决**: 角色一致性通过 Midjourney 变体保持近似视觉

### 案例 2：可口可乐 AI 广告 "Really enjoying their rice"（2024）
- **制作方**: Publicis London + The Mill
- **工具**: Stable Diffusion + Runway + Adobe 合成
- **创新**: 首个大规模投放的AI商业广告之一
- **流程**: 实拍厨房场景 → AI 扩展生成不同文化背景的家庭场景
- **信息来源**: Campaign Asia, The Drum 报道

### 案例 3："创战纪"风格短片（《光明王者》测试片，2024）
- **工具链**: Midjourney (角色图) → Runway Gen-2 (动作化) 
- **特别**: 角色LoRA训练后固定，保持同一演员跨场景出现
- **信息来源**: B站/YouTube AI 创作区 UP 主实战分享

---

## 八、结论与建议

### 行业认知共识
1. AI电影制作目前处于 **"辅助创作"(Copilot) 而非"独立制作"** 阶段
2. 最大瓶颈不是生成质量，而是 **一致性控制与叙事逻辑**
3. 工作流标准化正在进行，但尚未形成行业统一的 SOP
4. 商业广告是当前最成熟的可落地场景，其次是 MV/短宣

### 信源清单
- Runway Blog: https://runwayml.com/blog
- No Film School AI教程板块
- Midjourney Official Discord (Prompt-sharing频道)
- ComfyUI Community Workflows
- 可灵AI/快手生成式AI团队官方Medium/公众号

---

*本报告由 AIGC Film Master 技能整理，持续更新中。*
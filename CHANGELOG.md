# 更新日志

所有重大更改都会记录在本文件。按 [Keep a Changelog](https://keepachangelog.com/) 规范格式。

格式类别：`Added` / `Changed` / `Deprecated` / `Removed` / `Fixed` / `Security`

---

## [Unreleased]

### Added
- (待下次发布时填入)

---

## [1.0.0] — 2026-05-23

### Added

#### 核心文件
- `SKILL.md` — AIGC 创意导演操作系统（含 7 个心智模型 + 10 条 Playbook + 工具选型 + 工作流 SOP）
- `meta.json` — Skill 元数据（行业/视角/状态/来源统计）
- `prompts/thinking.md` — 遇到新问题时的思考提示词

#### 示例与测试
- `prototypes/brand-ad-60s.md` — 60秒品牌广告完整示例工作流（从Brief到交付的全链路）
- `prototypes/boundary-cases.md` — 6个边界测试案例（含输入/期望行为/验收标准）

#### 调研文件
- `references/research/01-figures.md` — 行业大佬图谱（12位核心从业者：祁军/Tim/Jacob Adler/Ben Affleck等）
- `references/research/02-tools.md` — 工具地图（14款视频生成工具 + 全链路AI辅助工具分类）
- `references/research/03-workflows.md` — 工作流 SOP（入门/资深/场景化 + 10失败模式 + 3案例）
- `references/research/04-canon.md` — 知识正典（20本必读书 + 14篇核心论文 + 30个核心概念）
- `references/research/05-sources.md` — 信息源（47条6类：播客/社区/公众号/B站/竞赛/学术）
- `references/research/06-glossary.md` — 术语/法规/标准（25技术术语 + 15创意术语 + 11版权法规）

#### Phase 5 升级
- `references/genre-playbooks/suspense-thriller.md` — 悬疑/惊悚 Playbook（叙事动作 + 镜头调度 + AIGC风险 + 质感锁定）
- `references/genre-playbooks/commercial-tvc.md` — 广告/TVC Playbook（策略锁定 + 6故事模式 + 节奏 + 质感锁定）
- `references/genre-playbooks/short-drama.md` — 竖屏短剧 Playbook（剧集引擎 + 9:16镜头 + 节奏 + 质感锁定）
- `references/genre-playbooks/black-humor.md` — 黑色幽默 Playbook（叙事动作 + 面无表情表演 + 节奏 + 质感锁定）
- `references/genre-playbooks/cultural-tourism.md` — 文旅 Playbook（叙事动作 + 镜头 + 节奏 + 质感锁定）
- `references/aigc-director-system.md` — AIGC 导演系统（含 6级可行性标签 + 导演护栏 + 交付物模板）
- `references/qa-risk-gates.md` — QA 10重质量门禁（故事/来源/AIGC可行性/交接/提示词/生成/长剧/合规/留存/交付）
- `references/synthesis.md` — 框架提炼（9大模块：心智模型 + Playbook + 工具栈 + 工作流 + 表达DNA + 质量基准 + 智识谱系 + 诚实边界 + Agentic Protocol）

### Changed
- `SKILL.md` — 新增 2.4.1 类型片差异化 SOP + 2.4.2 AIGC 导演可行性判断（6级标签）
- `references/synthesis.md` — 新增 2.6.3 AIGC 导演可行性标签 + 2.10 QA 质量门禁（10重）+ 交叉引用索引更新
- `meta.json` — 新增 `genre_playbooks` 字段 + Phase 5 更新说明 + `source_count` 统计

### Documentation
- `README.md` — 项目自述文件（快速开始 + 文件结构 + 核心内容 + 选型决策树 + 质量基准）
- `CONTRIBUTING.md` — 贡献指南（行为准则 + PR流程 + Commit格式 + 内容标准）
- `.gitignore` — Git 忽略配置

---

## 早期版本

[1.0.0-rc.1] — 2026-05-23（初始构建阶段）

- 内部开发版本，未发布

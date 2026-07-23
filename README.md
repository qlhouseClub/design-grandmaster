# Design Grandmaster

[![Validate](https://github.com/qlhouseClub/design-grandmaster/actions/workflows/validate.yml/badge.svg)](https://github.com/qlhouseClub/design-grandmaster/actions/workflows/validate.yml)
[![Release](https://img.shields.io/github/v/release/qlhouseClub/design-grandmaster?display_name=tag)](https://github.com/qlhouseClub/design-grandmaster/releases)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

面向高要求产品与视觉项目的设计宗师技能包。它同时处理业务目标、用户体验、设计规范、Design Token、品牌表达、审美判断、历史与当代视觉研究、交互、情绪体验、无障碍和工程交付。

它不会把“好看”简化成流行风格，也不会为了视觉表现破坏已有设计系统。

## 核心能力

- 既有设计规范与组件库的严格遵循
- Design Token 治理、映射和一致性审计
- 客户审美发现、参考与反参考分析
- 高级审美判断、视觉命题与设计裁决
- 历史、文化、材料和视觉潮流的研究与数字化转译
- 真实品牌资产、方向可视证明、决策留痕与运行验证
- 配色拓扑、留白与焦点几何、动效连续性和表达性交互
- 原子化设计、品牌、字体、色彩、排版、图像与动效
- 信息架构、用户流程、状态、交互和认知负荷
- 情绪体验、心理机制与用户自主性
- 响应式、国际化、无障碍与包容性设计
- 原型验证、设计批评、交付标注和实现 QA

## 核心原则

1. 用具体视觉证据了解客户审美，而不是依赖“高级、现代、有质感”等形容词。
2. 对历史、文化、陌生风格和当前潮流先研究再转译。
3. 先明确受众、任务、情绪和品牌意义，再选择视觉语言。
4. 完整应用优先解决业务、信息、流程、状态和可用性；纯视觉项目允许投入更深的审美研究。
5. 已批准的设计规范具有约束力，共享 Design Token 未经明确授权不得更改。
6. 原子化设计是组合模型，不是机械的文件夹分类法。
7. 趋势是一种视觉谱系，不是可以直接套用的皮肤。
8. 情绪设计必须服务于理解、信任和用户自主性。
9. 重要视觉决策必须用代表性成品证明，不能只让客户从文字风格标签中选择。
10. 灵感来源必须转成可解释、可测试的机制，而不是复制某位设计师或某张作品。

## 规范遵循

当项目已有设计系统时，技能默认采用：

```text
复用现有组件
→ 组合现有能力
→ 使用被允许的局部变体
→ 提出系统扩展建议
→ 获得授权后才修改共享规则
```

间距、字号、色彩、圆角、阴影和动效等数值必须解析到获准的 Token 或明确记录的技术例外。若间距体系提供 `12 / 16 / 20 / 24`，则 `15 / 21 / 23` 不会被视为“微调”，而是规范违例。

## 自适应工作路径

- **完整产品或应用：** 业务与体验优先，只在品牌关键节点进行必要的视觉研究。
- **品牌、文化、编辑、展览或旗舰视觉项目：** 深入进行客户审美发现、视觉语料研究和设计方向竞争。
- **既有设计系统项目：** 首先锁定规范版本、权威来源和 Token，不允许无授权漂移。
- **趋势项目：** 研究趋势的来源、机制、当前状态和过期风险，再决定是否以及如何使用。
- **可运行视觉产物：** 先做最小但真实的方向证明，再逐步扩展，并在目标运行环境中检查渲染、交互、响应式和异常状态。

## 目录结构

```text
design-grandmaster/
├── SKILL.md                         # 主入口、路径选择与质量门槛
├── agents/openai.yaml               # Codex 界面元数据
├── .github/workflows/               # 自动验证与版本发布
├── references/
│   ├── design-system-conformance.md
│   ├── aesthetic-discovery-research.md
│   ├── aesthetic-governor.md
│   ├── visual-trend-atlas.md
│   ├── visual-craft-grammar.md
│   ├── experience-strategy.md
│   ├── brand-and-visual-language.md
│   ├── atomic-design-system.md
│   ├── interaction-cognition-emotion.md
│   ├── accessibility-content-inclusion.md
│   ├── responsive-motion-data.md
│   ├── artifact-production-validation.md
│   ├── critique-prototype-handoff.md
│   ├── artifact-templates.md
│   └── canonical-sources.md
├── platforms/                       # 跨平台元数据与扣子桥接提示词
├── scripts/build_compat.py          # 生成 TRAE、OpenAI Plugin、扣子和便携包
├── COMPATIBILITY.md                 # 跨平台安装、限制与维护规则
├── CONTRIBUTING.md                  # 贡献规则
├── SECURITY.md                      # 私密安全报告
└── LICENSE                          # MIT 许可证
```

## 跨平台安装

仓库同时适配 Codex、ChatGPT、TRAE Work、Hermes、OpenClaw 和扣子。请选择实际使用的平台；不需要把所有版本都安装一遍。

不想在本地构建时，可以直接从 [GitHub Releases](https://github.com/qlhouseClub/design-grandmaster/releases) 下载 TRAE、OpenAI Plugin、扣子或便携 ZIP。

| 平台 | 推荐安装方式 | 安装后形态 |
|---|---|---|
| Codex / ChatGPT 桌面端 | 克隆到个人技能目录 | 原生 Agent Skill |
| ChatGPT Work / 团队 | 生成并安装 Plugin | OpenAI Plugin |
| TRAE Work / SOLO / IDE | 克隆到技能目录，或上传生成的 ZIP | 原生 Skill |
| Hermes Agent | 克隆到 Hermes 技能目录 | 原生 Skill |
| OpenClaw | 使用 Git 安装命令 | 原生 Agent Skill |
| 扣子 / Coze | 生成提示词与知识库包 | 提示词 + RAG 知识库 |

### Codex / ChatGPT 桌面端

Windows PowerShell：

```powershell
$skillDir = "$env:USERPROFILE\.codex\skills\design-grandmaster"
New-Item -ItemType Directory -Force (Split-Path $skillDir) | Out-Null
git clone https://github.com/qlhouseClub/design-grandmaster.git $skillDir
```

macOS / Linux：

```bash
skill_dir="$HOME/.codex/skills/design-grandmaster"
mkdir -p "$(dirname "$skill_dir")"
git clone https://github.com/qlhouseClub/design-grandmaster.git "$skill_dir"
```

若希望与其他兼容 Agent 共用技能，也可以把目标根目录改为 `~/.agents/skills/`。重启或刷新客户端后，即可通过“使用设计宗师……”等自然语言触发。

### ChatGPT Work / 团队 Plugin

先克隆仓库并生成 OpenAI Plugin：

```powershell
git clone https://github.com/qlhouseClub/design-grandmaster.git
Set-Location .\design-grandmaster
python .\scripts\build_compat.py --platform openai
codex.cmd plugin marketplace add .\dist\openai-marketplace
```

macOS / Linux 最后一条命令使用：

```bash
codex plugin marketplace add ./dist/openai-marketplace
```

重启 ChatGPT 桌面端，在 Plugins 中安装“设计宗师”。需要团队使用时，可从插件详情页分享到 ChatGPT 工作区。独立插件包为 `dist/openai/design-grandmaster-plugin.zip`。

### TRAE Work / SOLO / IDE

国内版全局安装：

```powershell
$skillDir = "$env:USERPROFILE\.trae-cn\skills\design-grandmaster"
New-Item -ItemType Directory -Force (Split-Path $skillDir) | Out-Null
git clone https://github.com/qlhouseClub/design-grandmaster.git $skillDir
```

国际版把 `.trae-cn` 改为 `.trae`。项目级安装则克隆或复制到：

```text
<项目>/.trae/skills/design-grandmaster/
```

也可以下载 Release 中的 `design-grandmaster.zip`，在 TRAE 的“设置 → 技能与命令/规则和技能 → 创建或上传技能”中导入。自行构建命令为：

```powershell
python .\scripts\build_compat.py --platform trae
```

### Hermes Agent

将完整仓库安装到 Hermes 个人技能目录，确保 `references/` 等引用文件一并保留：

```powershell
$skillDir = "$env:USERPROFILE\.hermes\skills\design-grandmaster"
New-Item -ItemType Directory -Force (Split-Path $skillDir) | Out-Null
git clone https://github.com/qlhouseClub/design-grandmaster.git $skillDir
```

macOS / Linux：

```bash
skill_dir="$HOME/.hermes/skills/design-grandmaster"
mkdir -p "$(dirname "$skill_dir")"
git clone https://github.com/qlhouseClub/design-grandmaster.git "$skill_dir"
```

安装后新建会话；若希望当前会话立即刷新，可在 Hermes 中执行 `/reset`。

### OpenClaw

安装到当前工作区：

```text
openclaw skills install git:qlhouseClub/design-grandmaster@main
```

安装为所有本地 Agent 共用的全局技能：

```text
openclaw skills install git:qlhouseClub/design-grandmaster@main --global
```

从已克隆的仓库根目录安装：

```text
openclaw skills install . --as design-grandmaster
```

### 扣子 / Coze

扣子不直接读取 Agent Skill 目录。可以下载 Release 中的 `design-grandmaster-coze.zip`，或自行生成：

```powershell
git clone https://github.com/qlhouseClub/design-grandmaster.git
Set-Location .\design-grandmaster
python .\scripts\build_compat.py --platform coze
```

然后在扣子中完成以下设置：

1. 将 `dist/coze/design-grandmaster/agent-prompt.md` 粘贴到智能体系统提示词。
2. 新建知识库，上传 `dist/coze/design-grandmaster/knowledge/` 中的全部 Markdown 文件。
3. 将知识库绑定到智能体并启用检索。
4. 按需要配置联网、Figma、代码库等插件或工作流。

### 生成全部平台包

已经克隆仓库时，可以一次生成所有适配产物：

```powershell
python .\scripts\build_compat.py --platform all
```

完整的平台边界、目录说明、维护规则和官方依据见 [COMPATIBILITY.md](COMPATIBILITY.md)。

## 使用示例

- “在不改变现有 Design Token 的前提下，为这个后台增加一个审批模块。”
- “先了解我的审美，再为品牌网站提出三条不同的视觉方向。”
- “研究唐代岩彩、矿物颜料和当代数字视觉，转译成一个可读的网站系统。”
- “判断液态玻璃是否适合这个金融应用，不要为了潮流牺牲可用性。”
- “审查这套界面里的间距、字体、组件和交互是否违反设计规范。”
- “把这个视觉方案提升到具有明确作者性和品牌辨识度的水平。”
- “从这些灵感中提取配色、版式、动效和交互机制，再做一套不照搬原作的项目语法。”

## Token 与研究策略

技能采用渐进式加载。普通产品设计不会自动加载完整的审美研究、趋势图谱和高级视觉裁决模块；只有视觉 ambition、文化风险或任务决策需要时才进入深度模式。

视觉调研以“新证据不再改变视觉语法、风险或方向空间”为停止条件，避免把无上限收集参考误认为专业。

产品交互研究优先查看真实上线流程，实验性网站与视觉作品用于拓展表达边界；两类证据不会混为一谈。高视觉方向先用代表性页面、幻灯片或关键帧证明，再进入批量生产。

## 本轮吸收与来源

本版本对 [Huashu Design](https://github.com/alchaincyf/huashu-design) 的真实资产、视觉方向证明、阶段决策与运行验证方法进行了重新设计，并保留其 [MIT 许可](https://github.com/alchaincyf/huashu-design/blob/master/LICENSE)来源说明。未吸收随机风格轮盘、模仿特定设计师、所有任务强制三稿、资产覆盖已批准规范等做法。

视觉工艺模块还基于 [Dreameryanyan 在 X 的公开策展内容](https://x.com/yanliudreamer)建立了二次研究路径，并核验了其引用的真实产品流程库 [Mobbin](https://mobbin.com/)、网页案例库 [Lapa Ninja](https://www.lapa.ninja/)、创意开发案例 [Codrops](https://tympanus.net/codrops/hub/author/the_bugged_dev/) 与开源编辑设计实验 [GC Minimal Zine Poster](https://github.com/LiamGvchi/gc-minimal-zine-poster)。技能吸收的是可迁移机制，不复制具体作品或个人风格。

## 重要默认值

- 规范优先于个人审美
- 共用 Design Token 默认只读
- 研究结论区分来源事实、直接观察、推断和设计转译
- 无障碍不是最终检查项
- 潮流不等于方向，效果不等于品味
- 高视觉要求必须形成可识别的设计命题，而不只是干净和精致
- 真实品牌资产必须核验来源、版本与权利，但不能凌驾于已批准的规范
- 重要方向用同内容、同资产、同场景的可视证明进行比较
- 可运行产物必须在实际运行环境中打开、检查和验证，不能只读源文件

## 状态

- YAML 元数据校验通过
- 本地引用链接校验通过
- 已验证既有 Token 约束在跨页面输出中的持续遵循
- 已验证历史文化视觉研究与当代数字转译流程
- 已加入真实资产清单、风险分级方向 Gate、视觉工艺语法与运行验证链路
- 已生成并校验 TRAE、OpenAI Plugin、扣子和便携适配产物

## 许可、贡献与安全

- 使用条款：[MIT License](LICENSE)
- 第三方研究与许可边界：[THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md)
- 贡献方式：[CONTRIBUTING.md](CONTRIBUTING.md)
- 私密报告安全问题：[SECURITY.md](SECURITY.md)

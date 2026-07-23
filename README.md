# Design Grandmaster

面向高要求产品与视觉项目的设计宗师技能包。它同时处理业务目标、用户体验、设计规范、Design Token、品牌表达、审美判断、历史与当代视觉研究、交互、情绪体验、无障碍和工程交付。

它不会把“好看”简化成流行风格，也不会为了视觉表现破坏已有设计系统。

## 核心能力

- 既有设计规范与组件库的严格遵循
- Design Token 治理、映射和一致性审计
- 客户审美发现、参考与反参考分析
- 高级审美判断、视觉命题与设计裁决
- 历史、文化、材料和视觉潮流的研究与数字化转译
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

## 目录结构

```text
design-grandmaster/
├── SKILL.md                         # 主入口、路径选择与质量门槛
├── agents/openai.yaml               # Codex 界面元数据
├── references/
│   ├── design-system-conformance.md
│   ├── aesthetic-discovery-research.md
│   ├── aesthetic-governor.md
│   ├── visual-trend-atlas.md
│   ├── experience-strategy.md
│   ├── brand-and-visual-language.md
│   ├── atomic-design-system.md
│   ├── interaction-cognition-emotion.md
│   ├── accessibility-content-inclusion.md
│   ├── responsive-motion-data.md
│   ├── critique-prototype-handoff.md
│   ├── artifact-templates.md
│   └── canonical-sources.md
├── platforms/                       # 跨平台元数据与扣子桥接提示词
├── scripts/build_compat.py          # 生成 TRAE、OpenAI Plugin、扣子和便携包
└── COMPATIBILITY.md                 # 跨平台安装、限制与维护规则
```

## 安装

将仓库克隆或复制到 Codex / ChatGPT 桌面端个人技能目录：

```powershell
git clone https://github.com/qlhouseClub/design-grandmaster.git "$env:USERPROFILE\.agents\skills\design-grandmaster"
```

重启或刷新 Codex 后，即可通过自然语言触发技能。

## 跨平台兼容

仓库同时适配 Codex、ChatGPT、TRAE Work、Hermes、OpenClaw 和扣子。Codex、TRAE、Hermes 与 OpenClaw 复用开放的 `SKILL.md` 结构；ChatGPT Work 使用生成的 Plugin；扣子使用系统提示词与知识库转换层。

完整安装方法、平台边界和生成命令见 [COMPATIBILITY.md](COMPATIBILITY.md)。

## 使用示例

- “在不改变现有 Design Token 的前提下，为这个后台增加一个审批模块。”
- “先了解我的审美，再为品牌网站提出三条不同的视觉方向。”
- “研究唐代岩彩、矿物颜料和当代数字视觉，转译成一个可读的网站系统。”
- “判断液态玻璃是否适合这个金融应用，不要为了潮流牺牲可用性。”
- “审查这套界面里的间距、字体、组件和交互是否违反设计规范。”
- “把这个视觉方案提升到具有明确作者性和品牌辨识度的水平。”

## Token 与研究策略

技能采用渐进式加载。普通产品设计不会自动加载完整的审美研究、趋势图谱和高级视觉裁决模块；只有视觉 ambition、文化风险或任务决策需要时才进入深度模式。

视觉调研以“新证据不再改变视觉语法、风险或方向空间”为停止条件，避免把无上限收集参考误认为专业。

## 重要默认值

- 规范优先于个人审美
- 共用 Design Token 默认只读
- 研究结论区分来源事实、直接观察、推断和设计转译
- 无障碍不是最终检查项
- 潮流不等于方向，效果不等于品味
- 高视觉要求必须形成可识别的设计命题，而不只是干净和精致

## 状态

- YAML 元数据校验通过
- 本地引用链接校验通过
- 已验证既有 Token 约束在跨页面输出中的持续遵循
- 已验证历史文化视觉研究与当代数字转译流程
- 已生成并校验 TRAE、OpenAI Plugin、扣子和便携适配产物

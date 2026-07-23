# 贡献指南

感谢你帮助改进 Design Grandmaster。

## 先确定变更属于哪一层

- 专业能力：修改 `SKILL.md` 或 `references/`
- OpenAI 展示元数据：修改 `agents/openai.yaml`
- 扣子行为桥接：修改 `platforms/coze/agent-prompt.md`
- 平台名称、版本与描述：修改 `platforms/manifest.json`
- 平台构建逻辑：修改 `scripts/build_compat.py`

不要手工编辑或提交 `dist/`。所有平台包必须从仓库中的唯一知识源重新生成。

## 贡献要求

1. 现有设计规范、Design Token 和组件契约优先于个人审美；不得引入无授权漂移。
2. 视觉参考必须记录来源、日期、观察、推断、转译机制和适用边界。
3. 不模仿在世设计师，不复制可识别作品，不提交未经许可的字体、图片、Logo、截图或品牌资产。
4. 新增视觉机制必须同时说明可读性、交互、无障碍、性能与降级方式。
5. 对潮流、平台规范和当前案例的陈述应实时核验，并保留原始来源。

## 本地验证

```powershell
python .\scripts\build_compat.py --platform all
```

提交前确认：

- `SKILL.md` 的名称与 `platforms/manifest.json` 一致
- 所有本地 Markdown 引用存在
- JSON 与 YAML 可以解析
- TRAE、OpenAI、扣子和便携包均能生成
- `git diff --check` 无错误

请使用不暴露私人邮箱的 Git 提交地址。安全问题按照 [SECURITY.md](SECURITY.md) 私密报告。

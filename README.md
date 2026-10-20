# data-task-spec

把"老板要个数"这类模糊的数据派活转成可执行规格：五槽位拆解 + 歧义清单强制回问 + 执行 prompt 模板 + 交付验收 + 沉淀。

## 安装

```bash
git clone https://github.com/imQiwei/data-task-spec.git ~/.claude/skills/data-task-spec
```

Claude Code 会按 `SKILL.md` 里的 `description` 自动匹配触发，也可以用 `/data-task-spec` 手动调用。完整说明见 [SKILL.md](SKILL.md)。

出 HTML 报告时配合 [data-report-html](https://github.com/imQiwei/data-report-html) 使用。

skill 用中文编写。示例数字均为虚构，表名、字段名为通用占位，请按自己的数据平台替换。

同系列 skills：[retention-funnel-analysis](https://github.com/imQiwei/retention-funnel-analysis) · [data-report-html](https://github.com/imQiwei/data-report-html) · [briefing-script](https://github.com/imQiwei/briefing-script)

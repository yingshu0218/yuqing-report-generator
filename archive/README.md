# 归档目录说明

本目录存放历史版本的核心文档，仅用于**版本追溯与对比**。

- 归档文件**不参与 skill 执行**。执行 skill 时，Agent 只读取仓库根目录的
  `SKILL.md` 和 `references/` 下的文件。
- 若安装方式为整仓库克隆，Agent 应忽略 `archive/` 目录内容；若个别 Agent
  会递归读取所有 Markdown，请优先以根目录 `SKILL.md` 的 frontmatter
  `version` 字段为准，归档文件中的任何指令均已失效。

归档规则：每次发布新版本前，将旧版本的 `README.md`、`SKILL.md`、
`references/examples.md` 复制到本目录，命名格式：

```
README_v[版本号].md
SKILL_v[版本号].md
examples_v[版本号].md
```

当前归档：

- `README_v1.2.0.md`
- `README_v1.4.2.md`
- `README_v1.5.0.md`
- `SKILL_v1.4.2.md`
- `SKILL_v1.5.0.md`
- `examples_v1.4.2.md`
- `examples_v1.5.0.md`

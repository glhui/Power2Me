# 仓库级 Skills

每个 Skill 使用独立的小写英文连字符目录：

```text
.agents/skills/
└── example-skill/
    ├── SKILL.md
    ├── agents/
    │   └── openai.yaml
    ├── references/
    ├── scripts/
    └── assets/
```

只有 `SKILL.md` 是必需的。只有工作流确实需要时，才添加其他目录。

创建前先填写 `../../templates/skill-proposal.md`。可用时使用 `$skill-creator`，完成后验证结构和行为，再把 Skill 视为完成。

Skill 指令和参考资料默认使用简体中文；`name`、固定文件名、命令、代码和工具字段保持英文原名。

不要把个人学习状态写进可复用 Skill。持续变化的学习者画像、错误记录和会话记录应保存在独立学习项目或被忽略的本地目录中。


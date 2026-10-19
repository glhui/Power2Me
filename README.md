# Power2Me

Power2Me 是一个适合 Git 同步的学习工作区，用于通过小型实验、行为评估和基于证据的迭代学习如何设计可靠的 Agent Skill。

## 快速开始

1. 阅读[学习路线](docs/learning-path.md)。
2. 阅读[Skill 设计指南](docs/skill-design.md)。
3. 复制并填写 [Skill 提案模板](templates/skill-proposal.md)。
4. 在 [`.agents/skills/`](.agents/skills/README.md) 中创建仓库级 Skill。
5. 按照[行为评估说明](evals/README.md)定义案例。
6. 把实际结果写入[学习日志](notes/learning-log.md)。

## 项目结构

```text
.
├── AGENTS.md                 Agent 在本仓库中的工作约定
├── README.md                 人类使用者的项目入口
├── .agents/
│   └── skills/               随仓库同步的 Skill
├── docs/
│   ├── learning-path.md      渐进练习和完成标准
│   ├── skill-design.md       Skill 结构和设计判断
│   └── update-policy.md      基于证据的更新规则
├── evals/
│   └── README.md             行为评估约定
├── notes/
│   ├── decisions.md          长期有效的决策
│   └── learning-log.md       实验和实际结果
└── templates/
    └── skill-proposal.md     Skill 提案与验证模板
```

## 中文约定

学习材料、Skill 指令和 Agent 输出默认使用简体中文。工具要求的固定文件名、代码标识符、命令和 YAML 字段保持原样。重要术语首次出现时可以同时标注英文，便于检索官方资料。

## 跨设备使用

受 Git 跟踪的文件全部使用仓库相对路径。在其他设备克隆仓库后，从仓库根目录打开支持 Agent 的编码工具，根目录 `AGENTS.md` 会提供工作约定。不同产品的安装或启用步骤不应写死在可移植的 Skill 源文件中。

## 隐私

不要提交凭据、私有题库、无权再分发的受版权保护材料或敏感个人学习记录。本地专用材料应放入 `.git/info/exclude` 或明确忽略的私有目录。


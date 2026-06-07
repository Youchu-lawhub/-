# Youchu LawHub Skills

A curated collection of AI agent skill packages for legal professionals. Each skill package is designed to automate and standardize specific legal workflows.

精选 AI 智能体法律技能包合集，每个技能包旨在自动化和标准化特定的法律工作流程。

## Skill Packages / 技能包列表

| Skill | Description | 说明 |
|-------|-------------|------|
| [gutachten-civil-case](./gutachten-civil-case/) | Gutachten-style civil law case analysis using the Anspruchsgrundlage method | 基于请求权基础方法的鉴定式民法案例分析 |

## Structure / 仓库结构

```
youchu-lawhub-skills/
├── README.md
├── LICENSE
└── <skill-name>/           # Each skill lives in its own directory
    ├── SKILL.md            # Skill definition (required)
    ├── workflow/           # Step-by-step workflow documents
    ├── methodology/        # Methodology references
    ├── examples/           # Example outputs and templates
    └── format/             # Output format specifications
```

## Usage / 使用方法

These skill packages are designed for AI coding assistants and agent platforms. To install a skill, reference the `SKILL.md` file in the corresponding skill directory.

这些技能包适用于 AI 编程助手和智能体平台。安装技能时，引用对应技能目录中的 `SKILL.md` 文件即可。

## License / 许可

See [LICENSE](./LICENSE) for details.

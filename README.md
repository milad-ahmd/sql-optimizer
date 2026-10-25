> [!NOTE]
> **This skill now lives in the main collection: [milad-ahmd/agent-skills](https://github.com/milad-ahmd/agent-skills/tree/main/skills/sql-optimizer)**. Please ⭐ star it there; that's where updates land first.
> Docs: **https://milad-ahmd.github.io/agent-skills/skills/sql-optimizer/** · Claude Code: `/plugin install all-skills --marketplace milad-ahmd/agent-skills`

<div align="center">

# ⚡ sql-optimizer

**Explain slow SQL queries and get index and rewrite fixes. An Agent Skill for Claude Code, Cline, Cursor, Codex and other AI coding agents.**

[![License: MIT](https://img.shields.io/github/license/milad-ahmd/sql-optimizer)](LICENSE)
[![Stars](https://img.shields.io/github/stars/milad-ahmd/sql-optimizer?style=social)](https://github.com/milad-ahmd/sql-optimizer)
![Category](https://img.shields.io/badge/category-Backend%20&%20Data-blue)
![Works with](https://img.shields.io/badge/works%20with-Claude%20Code%20%7C%20Cline%20%7C%20Cursor%20%7C%20Codex-8A2BE2)

[Install](#-install) · [Usage](#-usage) · [How it works](skills/sql-optimizer/SKILL.md) · [All skills](https://github.com/milad-ahmd/agent-skills)

</div>

> Part of **[agent-skills](https://github.com/milad-ahmd/agent-skills)**, a growing collection of practical skills for AI coding agents.

## 📦 Install

**One command (installs the whole collection):**

```bash
curl -fsSL https://raw.githubusercontent.com/milad-ahmd/agent-skills/main/install.sh | bash -s -- sql-optimizer
```

**Manually (Claude Code):**

```bash
git clone https://github.com/milad-ahmd/sql-optimizer /tmp/sql-optimizer
mkdir -p ~/.claude/skills && cp -r /tmp/sql-optimizer/skills/sql-optimizer ~/.claude/skills/
```

**Per project:** copy `skills/sql-optimizer` into `<project>/.claude/skills/`.
**Any other agent:** paste [`SKILL.md`](skills/sql-optimizer/SKILL.md) into your rules or system prompt.

## 💬 Usage

Just ask your agent:

```text
Why is this query slow?
Find N+1 queries in this API
```

The full workflow, rules and output format are in [`SKILL.md`](skills/sql-optimizer/SKILL.md).

## 🧩 More skills

See the full collection: **[milad-ahmd/agent-skills](https://github.com/milad-ahmd/agent-skills)**.

## 🤝 Contributing

Issues and PRs are welcome, especially real-world before/after examples.

## 📄 License

[MIT](LICENSE) © Milad Ahmadi

<div align="center">

**If this skill saved you time, a ⭐ helps others find it.**

</div>

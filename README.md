# Project Audit Skill for Claude Code

A [Claude Code](https://docs.anthropic.com/en/docs/claude-code) skill that performs a comprehensive project audit -- evaluating whether the current implementation achieves its original goals, identifying gaps, and proposing a prioritized improvement roadmap -- in a single `/project-audit` command. Requires the Claude Code CLI.

## What's Included

- **SKILL.md** -- The skill definition that drives the `/project-audit` command. It walks through a structured six-phase methodology: scoping the review, discovering original goals, mapping the current implementation (including dependency health), analyzing goal vs. reality with a prioritized gap table, running a qualitative assessment (architecture, reliability, maintainability, testability, security, performance, CI/CD), delivering a clear verdict, and producing a tiered improvement roadmap with concrete next steps.

## Installation

Clone this repository:

```sh
git clone https://github.com/ai-awesome/skill-project-audit.git
```

Then install the skill from the local path:

```sh
claude mcp add-skill /path/to/skill-project-audit
```

Or install directly from the remote URL:

```sh
claude mcp add-skill https://github.com/ai-awesome/skill-project-audit
```

## Customization

The skill is defined entirely in SKILL.md. Edit it to fit your workflow -- adjust the review phases, change the priority definitions, or modify the output format.

## Contributing

1. Fork this repository and create a feature branch.
2. Make your changes and ensure they are consistent with the existing style.
3. Submit a pull request with a clear description of what you changed and why.

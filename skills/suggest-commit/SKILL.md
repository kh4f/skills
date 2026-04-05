---
name: suggest-commit
description: Suggest conventional commit messages from Git changes. Use when asked to suggest a commit message.
---

## Workflow
1. Analyze staged changes (fallback to unstaged if empty)
2. Use any user note as supporting context for intent, motivation, or footer details
3. Follow the [commit message guidelines](references/commit-guidelines.md)
5. Produce three commit message options, each in its own fenced `markdown` code block
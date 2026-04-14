---
name: git-commit
description: Auto-commit changes after a Wingman skill completes
metadata:
  author: github-spec-kit
  source: speckit-git-commit
user-invocable: true
disable-model-invocation: true
---

Forward `$ARGUMENTS` and delegate to `{Skill: speckit-git-commit}`. If it is not available, run `{Skill: init}` first to install it.

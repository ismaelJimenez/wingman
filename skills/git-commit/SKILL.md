---
name: git-commit
description: Auto-commit changes after a Wingman skill completes
metadata:
  author: github-spec-kit
  source: speckit-git-commit
user-invocable: true
disable-model-invocation: true
---

Forward `$ARGUMENTS` and delegate to `{Skill: speckit-git-commit}`. If it is not available, ask the user for confirmation to run `{Skill: init}` to install spec-kit skills. If confirmed, run init, then ask the user to restart the session and re-run the command so the new skills are available.

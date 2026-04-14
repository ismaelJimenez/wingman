---
name: git-feature
description: Create a feature branch with sequential or timestamp numbering
metadata:
  author: "github-spec-kit"
  source: "speckit-git-feature"
user-invocable: true
disable-model-invocation: true
---

Forward `$ARGUMENTS` and delegate to `{Skill: speckit-git-feature}`. If it is not available, ask the user for confirmation to run `{Skill: init}` to install spec-kit skills. If confirmed, run init, then ask the user to restart the session and re-run the command so the new skills are available.

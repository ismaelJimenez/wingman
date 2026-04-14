---
name: git-feature
description: Create a feature branch with sequential or timestamp numbering
metadata:
  author: "github-spec-kit"
  source: "speckit-git-feature"
user-invocable: true
disable-model-invocation: true
---

Forward `$ARGUMENTS` and delegate to `{Skill: speckit-git-feature}`. If it is not available, run `{Skill: init}` first to install it.

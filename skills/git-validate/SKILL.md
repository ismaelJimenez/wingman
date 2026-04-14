---
name: git-validate
description: Validate current branch follows feature branch naming conventions
metadata:
  author: "github-spec-kit"
  source: "speckit-git-validate"
user-invocable: true
disable-model-invocation: true
---

Forward `$ARGUMENTS` and delegate to `{Skill: speckit-git-validate}`. If it is not available, run `{Skill: init}` first to install it.

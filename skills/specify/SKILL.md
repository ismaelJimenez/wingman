---
name: specify
description: "Create or update the feature specification from a natural language feature description."
argument-hint: "Describe the feature you want to specify"
metadata:
  author: "github-spec-kit"
  source: "speckit-specify"
user-invocable: true
disable-model-invocation: true
---

Forward `$ARGUMENTS` and delegate to `{Skill: speckit-specify}`. If it is not available, run `{Skill: init}` first to install it.

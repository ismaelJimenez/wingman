---
name: constitution
description: "Create or update the project constitution from interactive or provided principle inputs, ensuring all dependent templates stay in sync."
argument-hint: "Principles or values for the project constitution"
metadata:
  author: "github-spec-kit"
  source: "speckit-constitution"
user-invocable: true
disable-model-invocation: true
---

Forward `$ARGUMENTS` and delegate to `{Skill: speckit-constitution}`. If it is not available, run `{Skill: init}` first to install it.

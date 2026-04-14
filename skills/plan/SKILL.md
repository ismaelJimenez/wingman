---
name: plan
description: "Execute the implementation planning workflow using the plan template to generate design artifacts."
argument-hint: "Optional guidance for the planning phase"
metadata:
  author: "github-spec-kit"
  source: "speckit-plan"
user-invocable: true
disable-model-invocation: true
---

Forward `$ARGUMENTS` and delegate to `{Skill: speckit-plan}`. If it is not available, run `{Skill: init}` first to install it.

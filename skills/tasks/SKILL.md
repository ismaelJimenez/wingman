---
name: tasks
description: "Generate an actionable, dependency-ordered tasks.md for the feature based on available design artifacts."
argument-hint: "Optional task generation constraints"
metadata:
  author: "github-spec-kit"
  source: "speckit-tasks"
user-invocable: true
disable-model-invocation: true
---

Forward `$ARGUMENTS` and delegate to `{Skill: speckit-tasks}`. If it is not available, run `{Skill: init}` first to install it.

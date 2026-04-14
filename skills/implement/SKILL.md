---
name: implement
description: "Execute the implementation plan by processing and executing all tasks defined in tasks.md"
argument-hint: "Optional implementation guidance or task filter"
metadata:
  author: "github-spec-kit"
  source: "speckit-implement"
user-invocable: true
disable-model-invocation: true
---

Forward `$ARGUMENTS` and delegate to `{Skill: speckit-implement}`. If it is not available, ask the user for confirmation to run `{Skill: init}` to install spec-kit skills. If confirmed, run init, then ask the user to restart the session and re-run the command so the new skills are available.

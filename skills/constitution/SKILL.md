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

Forward `$ARGUMENTS` and delegate to `{Skill: speckit-constitution}`. If it is not available, ask the user for confirmation to run `{Skill: init}` to install spec-kit skills. If confirmed, run init, then ask the user to restart the session and re-run the command so the new skills are available.

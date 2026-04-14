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

Forward `$ARGUMENTS` and delegate to `{Skill: speckit-specify}`. If it is not available, ask the user for confirmation to run `{Skill: init}` to install spec-kit skills. If confirmed, run init, then ask the user to restart the session and re-run the command so the new skills are available.

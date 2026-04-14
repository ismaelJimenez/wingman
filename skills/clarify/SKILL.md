---
name: clarify
description: "Identify underspecified areas in the current feature spec by asking up to 5 highly targeted clarification questions and encoding answers back into the spec."
argument-hint: "Optional areas to clarify in the spec"
metadata:
  author: "github-spec-kit"
  source: "speckit-clarify"
user-invocable: true
disable-model-invocation: true
---

Forward `$ARGUMENTS` and delegate to `{Skill: speckit-clarify}`. If it is not available, ask the user for confirmation to run `{Skill: init}` to install spec-kit skills. If confirmed, run init, then ask the user to restart the session and re-run the command so the new skills are available.

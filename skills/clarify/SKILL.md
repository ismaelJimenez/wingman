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

Forward `$ARGUMENTS` and delegate to `{Skill: speckit-clarify}`. If it is not available, run `{Skill: init}` first to install it.

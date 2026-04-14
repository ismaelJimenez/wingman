---
name: checklist
description: "Generate a custom checklist for the current feature based on user requirements."
argument-hint: "Domain or focus area for the checklist"
metadata:
  author: "github-spec-kit"
  source: "speckit-checklist"
user-invocable: true
disable-model-invocation: true
---

Forward `$ARGUMENTS` and delegate to `{Skill: speckit-checklist}`. If it is not available, run `{Skill: init}` first to install it.

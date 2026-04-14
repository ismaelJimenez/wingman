---
name: analyze
description: "Perform a non-destructive cross-artifact consistency and quality analysis across spec.md, plan.md, and tasks.md after task generation."
argument-hint: "Optional focus areas for analysis"
metadata:
  author: "github-spec-kit"
  source: "speckit-analyze"
user-invocable: true
disable-model-invocation: true
---

Forward `$ARGUMENTS` and delegate to `{Skill: speckit-analyze}`. If it is not available, run `{Skill: init}` first to install it.

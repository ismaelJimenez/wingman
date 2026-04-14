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

Forward `$ARGUMENTS` and delegate to `{Skill: speckit-analyze}`. If it is not available, ask the user for confirmation to run `{Skill: init}` to install spec-kit skills. If confirmed, run init, then ask the user to restart the session and re-run the command so the new skills are available.

---
name: tasks-to-issues
description: "Convert existing tasks into actionable, dependency-ordered GitHub issues for the feature based on available design artifacts."
argument-hint: "Optional filter or label for GitHub issues"
metadata:
  author: "github-spec-kit"
  source: "speckit-taskstoissues"
user-invocable: true
disable-model-invocation: true
---

Forward `$ARGUMENTS` and delegate to `{Skill: speckit-taskstoissues}`. If it is not available, run `{Skill: init}` first to install it.

---
name: git-validate
description: Validate current branch follows feature branch naming conventions
metadata:
  author: "github-spec-kit"
  source: "speckit-git-validate"
user-invocable: true
disable-model-invocation: true
---

Forward `$ARGUMENTS` and delegate to `{Skill: speckit-git-validate}`. If it is not available, ask the user for confirmation to run `{Skill: init}` to install spec-kit skills. If confirmed, run init, then ask the user to restart the session and re-run the command so the new skills are available.

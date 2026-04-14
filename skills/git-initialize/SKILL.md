---
name: git-initialize
description: Initialize a Git repository with an initial commit
metadata:
  author: "github-spec-kit"
  source: "speckit-git-initialize"
user-invocable: true
disable-model-invocation: true
---

Forward `$ARGUMENTS` and delegate to `{Skill: speckit-git-initialize}`. If it is not available, ask the user for confirmation to run `{Skill: init}` to install spec-kit skills. If confirmed, run init, then ask the user to restart the session and re-run the command so the new skills are available.

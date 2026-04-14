---
name: git-initialize
description: Initialize a Git repository with an initial commit
metadata:
  author: "github-spec-kit"
  source: "speckit-git-initialize"
user-invocable: true
disable-model-invocation: true
---

Forward `$ARGUMENTS` and delegate to `{Skill: speckit-git-initialize}`. If it is not available, run `{Skill: init}` first to install it.

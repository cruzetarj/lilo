---
name: git-release
description: Use when the user asks to inspect Git status, stage, commit, pull, or push this project.
---

Before changing Git state, inspect the current branch, remotes, and working tree. Preserve all existing user changes. Stage explicit paths and review the staged summary before committing. Never force-push, reset, or discard changes unless explicitly requested. Commit and push only when requested. If authentication is needed, pause and let the user authenticate directly; never ask for or echo passwords or tokens.

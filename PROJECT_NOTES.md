# codeWhale-like-codex Project Notes

This repository is an independent GitHub project based on CodeWhale. The
CodeWhale source tree is the project root, so normal build and development
commands should be run from this directory.

## Remotes

- `origin`: https://github.com/q1692306918/codeWhale-like-codex.git
- `upstream`: https://github.com/Hmbown/CodeWhale.git

Use `origin` for this project and `upstream` only to fetch CodeWhale updates.

## Codex Reference

The local `codex/` directory, when present, is an external reference checkout
only. It is ignored by Git, not vendored, and not a submodule.

Do not copy codex source into this repository unless you intentionally accept
the Apache 2.0 redistribution and notice obligations for the copied material.

## Upstream Sync

Fetch CodeWhale updates with:

```powershell
git fetch upstream
```

Because this repository has its own history, review upstream changes before
merging or cherry-picking them into `main`.

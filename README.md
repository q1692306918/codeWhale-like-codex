# codeWhale-like-codex

This repository is a personal integration workspace that tracks two upstream
open-source projects as Git submodules:

- `CodeWhale`: https://github.com/Hmbown/CodeWhale.git
- `codex`: https://github.com/openai/codex.git

## License Notes

This repository currently stores submodule pointers and project notes. The
upstream projects keep their own licenses inside their directories.

- `CodeWhale` is licensed under the MIT License. When copying, modifying, or
  redistributing substantial parts of it, keep the original copyright notice
  and MIT license text.
- `codex` is licensed under the Apache License 2.0 and includes a `NOTICE`
  file. When copying, modifying, or redistributing it, keep the Apache 2.0
  license, preserve required notices, keep the `NOTICE` information where
  applicable, and mark modified files when required by the license.

This is not the official repository for either upstream project. Do not remove
or obscure upstream attribution.

## Updating Upstreams

To fetch and move a submodule to the latest upstream `main` commit:

```powershell
git submodule update --remote --merge CodeWhale
git submodule update --remote --merge codex
git status
git add CodeWhale codex
git commit -m "Update upstream submodules"
```

If you make local changes inside a submodule, treat that submodule like its own
Git repository: commit your changes on a branch, then merge or rebase upstream
updates and resolve conflicts.

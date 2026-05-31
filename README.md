# codeWhale-like-codex

This repository vendors two upstream open-source projects:

- `CodeWhale`
- `codex`

The upstream source trees are kept in full under this repository, and each one
retains its own original license file and notices.

## License Notes

- `CodeWhale` is MIT licensed.
- `codex` is Apache 2.0 licensed and includes a `NOTICE` file.

When you redistribute this repository or derivatives of it, keep the upstream
license files, preserve attribution, and keep the `NOTICE` material from
`codex` where required. This repository is not the official upstream repo.

## Updating Upstreams

Because the projects are vendored, upgrades are manual but still straightforward:

1. Pull the upstream change into the vendored directory.
2. Review the diff and keep the license/notice files intact.
3. Commit the updated vendor tree in this repository.

If you want less maintenance, switch back to submodules or track your own forks
instead of vendoring.

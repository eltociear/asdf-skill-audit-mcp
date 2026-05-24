# asdf-skill-audit-mcp

[asdf](https://asdf-vm.com/) (and [mise](https://mise.jdx.dev/)) plugin for
[`skill-audit-mcp`](https://github.com/eltociear/skill-audit-mcp) — an MCP
server + CLI that audits MCP servers for supply-chain attacks.

## Install

```bash
asdf plugin add skill-audit-mcp https://github.com/eltociear/asdf-skill-audit-mcp.git
asdf install skill-audit-mcp latest
asdf global  skill-audit-mcp latest
```

mise:

```bash
mise use --global asdf:eltociear/asdf-skill-audit-mcp@latest
```

## Dependencies

- `bash`, `curl`, `tar`, `git`
- `python3` (the upstream scanner is Python 3.11+, stdlib-only)

## Why

Most MCP users today install via `pip install` or `npx` or `brew install`.
asdf/mise users want pinned, project-local versions managed alongside
node/python/ruby/etc. This plugin gives them parity.

## License

[CC0](LICENSE).

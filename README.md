<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/wordmark-dark.svg">
    <img src="assets/wordmark-light.svg" width="420" alt="://attainable">
  </picture>
</p>

# attain, the ://attainable CLI

The [://attainable](https://attainable.software) CLI: humans collaborate and agents build. This repository holds its
releases for macOS, Linux and Windows.

## Install

```sh
brew install attainable-engineer/tap/attain          # macOS and Linux (Homebrew)
winget install AttainableEngineer.Attain             # Windows (winget)
scoop bucket add attainable https://github.com/attainable-engineer/scoop-bucket
scoop install attainable/attain                      # Windows (Scoop)
```

On Debian/Ubuntu, Fedora/RHEL or Alpine, install the `.deb`, `.rpm` or `.apk` from the
[latest release](https://github.com/attainable-engineer/attain-cli/releases/latest), e.g.
`sudo apt install ./attain_*_amd64.deb`. Archives for every platform, and `SHA256SUMS`, are there too.

## Use

```sh
attain login              # paste a personal access token from your profile at https://attainable.software
attain workspaces
attain products list
attain build next > BUILD.md
attain mcp                # the MCP tools over stdio, e.g. claude mcp add attain -- attain mcp
```

`attain --help` lists every command.

## Links

- Documentation: https://attainable.software/docs#cli
- MCP server for AI apps: [attainable-engineer/attainable-mcp](https://github.com/attainable-engineer/attainable-mcp)
- Privacy policy: https://attainable.software/privacy
- Terms of Service: https://attainable.software/terms

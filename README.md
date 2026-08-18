# LayerV Homebrew Tap

Homebrew packages for LayerV tools.

## Install

```bash
brew tap layervai/tap
brew install qurl
```

## Available Packages

| Package | Type | Description |
|---------|------|-------------|
| `qurl` | Cask | qURL CLI - manage secure links from the command line |

The `qurl` cask is published automatically by GoReleaser when
[qurl-integrations](https://github.com/layervai/qurl-integrations) cuts a CLI
release. It installs the binary, shell completions (bash/zsh/fish), and man
pages on macOS and Linux.

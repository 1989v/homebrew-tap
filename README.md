# homebrew-tap

Homebrew tap for [muxbar](https://github.com/1989v/muxbar).

## Usage

```bash
brew install --cask 1989v/tap/muxbar
```

Homebrew resolves `1989v/tap/...` to this repository (`1989v/homebrew-tap`) automatically.

## Casks

| Cask | Description |
|------|-------------|
| [`muxbar`](Casks/muxbar.rb) | macOS menu bar app for tmux session management + caffeinate toggle |

## Uninstall

```bash
brew uninstall --cask muxbar
brew uninstall --zap --cask muxbar   # also remove config + preferences
```

# GitHook Global Hook to capture photos on commit

## Requirements:

- Linux: `fswebcam` (sudo apt install fswebcam)
- macOS: `imagesnap` (brew install imagesnap)

## Installation

1. `git config --global core.hooksPath ~/.githooks`
2. `mkdir -p ~/.githooks`
3. Copy the `pre-commit` file to `~/.githooks/`
4. `chmod +x ~/.githooks/pre-commit`

## Uninstall

```bash
rm ~/.githooks/pre-commit
git config --global --unset core.hooksPath
```

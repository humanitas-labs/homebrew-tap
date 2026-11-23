# Humanitas Labs Homebrew tap

Casks for Humanitas Labs apps.

```sh
brew tap humanitas-labs/tap
brew trust humanitas-labs/tap
brew install --cask sirius
```

Homebrew loads casks from a tap outside its own only once you trust it; `brew trust` is that step.

| Cask | App |
|---|---|
| `sirius` | [Sirius](https://github.com/humanitas-labs/sirius), for macOS 14+ on Apple Silicon |

Sirius updates itself once installed; `brew upgrade --cask sirius` works too.

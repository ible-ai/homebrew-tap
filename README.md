# homebrew-tap

Homebrew tap for [ible.ai](https://ible.ai) projects.

## mutible

[mutible](https://mut.ible.ai) ([source](https://github.com/ible-ai/mutible)): take back your space. Quickly explore your files, open and render just about anything, edit it in realtime, or watch your agents work through it all.

```
brew install --cask ible-ai/tap/mutible
```

mutible was called minicode until 1.6.0; `e-c-hansen/tap/minicode` points here.

The app is ad-hoc signed but not notarized, so the cask clears the macOS
quarantine flag on install and it opens without a Gatekeeper warning.

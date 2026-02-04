# Homebrew Tap

This is the Homebrew tap for `TobiSchelling`.

## Install

```bash
brew tap TobiSchelling/tap
brew install colibri
```

If you have another tap with the same formula name installed, use the fully-qualified name:

```bash
brew install TobiSchelling/tap/colibri
```

## Available Formulae

- `colibri`: local-first RAG for technical books and notes

## Maintainers

- Update `Formula/colibri.rb` to a tagged release artifact URL and SHA-256.
- Regenerate Python dependency resource blocks:

```bash
brew update-python-resources colibri
```

# Homebrew tap for Airbag

[Airbag](https://github.com/a1murt/airbag) is undo for AI coding agents on macOS: it snapshots your project before every
command Claude Code, Codex, Cursor, Gemini CLI or Copilot CLI runs, so a deleted folder, a `git reset --hard` or a
wiped `.env` is one click back.

```bash
brew install --cask a1murt/airbag/airbag
```

`brew upgrade` keeps your agents connected; `brew uninstall --cask airbag` removes Airbag's hooks from every agent
(`--zap` also deletes the snapshots).

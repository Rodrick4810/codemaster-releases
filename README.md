# Codemaster

Releases of Codemaster, a small, fast editor for SQL and Python on macOS: a SwiftUI app over a
Rust core, with its own Neovim-style vim engine, consoles for Redshift, PostgreSQL and MySQL,
and Claude Code, Codex and Kiro as chat agents.

This repository holds the built app only, as a DMG on each [release](https://github.com/Rodrick4810/codemaster-releases/releases).
The source is private.

## Install

```sh
brew install --cask rodrick4810/tap/codemaster
```

Or download the DMG from the latest release and drag Codemaster to Applications.

Needs macOS 26.0 or later on Apple silicon.

## First launch

The app is signed with its author's own certificate, not an Apple Developer ID, and isn't
notarized, so macOS blocks it the first time. Open it once, then choose **Open Anyway** in
System Settings › Privacy & Security. Updates signed the same way keep that approval.

# TokenKite

Track your AI spending across Claude Code, Cursor, and more — all from your Mac menu bar.

[![Download](https://img.shields.io/github/v/release/AAlcinesio/tokenkite?label=Download&style=flat-square)](https://github.com/AAlcinesio/tokenkite/releases/latest)
[![macOS](https://img.shields.io/badge/macOS-14.0%2B-blue?style=flat-square)](https://github.com/AAlcinesio/tokenkite/releases/latest)
[![Website](https://img.shields.io/badge/Website-tokenkite.com-blue?style=flat-square)](https://tokenkite.com)

## Features

- **Claude Code tracking** — Automatic parsing of usage logs from `~/.claude/projects/`
- **Cursor tracking** — Real-time billing data from Cursor's API
- **Quota monitoring** — See your Claude subscription usage (Pro/Max)
- **Menu bar app** — Quick access without leaving your workflow
- **Privacy first** — All data stays on your Mac, no cloud sync

## Installation

1. Download the latest `.dmg` from [Releases](https://github.com/AAlcinesio/tokenkite/releases/latest)
2. Open the DMG and drag TokenKite to Applications
3. Launch TokenKite from Applications
4. Grant any requested permissions (for reading usage logs)

## Requirements

- macOS 14.0 (Sonoma) or later
- Claude Code and/or Cursor installed

## How It Works

TokenKite reads your local usage data:

| Service | Data Source | What's Tracked |
|---------|-------------|----------------|
| Claude Code | `~/.claude/projects/**/*.jsonl` | Token usage, model breakdown, costs |
| Cursor | Local Cursor API | Billing data, request counts |

No API keys required for basic tracking. Your data never leaves your machine.

## Privacy

- **100% local** — No cloud sync, no telemetry, no analytics
- **Read-only** — TokenKite only reads data, never modifies it
- **Open tracking** — See exactly what files are accessed in Settings

## Support

- [Report a bug](https://github.com/AAlcinesio/tokenkite/issues/new?template=bug_report.md)
- [Request a feature](https://github.com/AAlcinesio/tokenkite/issues/new?template=feature_request.md)

## License

MIT License — see [LICENSE](LICENSE)

# CE BOT — Opus 4.7 Trading Bot

Autonomous swing-trading agent on top of Claude Code. Five cloud routines fire each
weekday; each is a fresh Claude run that reads memory from git, pulls live state,
acts on hard rules, writes new memory, and commits back to main.

## Quickstart (local)

1. `cp env.template .env` and fill in Alpaca (paper), Perplexity, Telegram keys.
2. `chmod +x scripts/*.sh`
3. Open this repo in Claude Code, run `/portfolio` to smoke-test.

## Quickstart (cloud)

See `routines/README.md` and the guide's Part 7.

## Layout

- `CLAUDE.md` — agent rulebook, auto-loaded each session
- `scripts/` — the only way the bot touches external APIs
- `memory/` — persistent state (committed to main)
- `routines/` — cloud-routine prompts (prod)
- `.claude/commands/` — local slash commands (dev / ad-hoc)

## Mode

**Paper by default.** Live requires explicit in-session confirmation.

## Goal

Beat SPY on a risk-adjusted basis over the challenge window.

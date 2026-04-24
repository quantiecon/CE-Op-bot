# Cloud Routines

Each `.md` file here is pasted verbatim into a Claude Code cloud routine's prompt
field. They are load-bearing — do not paraphrase. The env-var check block and the
commit-and-push step must survive intact or the bot silently fails.

## Cron schedules (America/Chicago)

| Routine        | Cron            | When                          |
|----------------|-----------------|-------------------------------|
| pre-market     | `0 6 * * 1-5`   | 6:00 AM weekdays              |
| market-open    | `30 8 * * 1-5`  | 8:30 AM weekdays (bell)       |
| midday         | `0 12 * * 1-5`  | noon weekdays                 |
| daily-summary  | `0 15 * * 1-5`  | 3:00 PM weekdays (close)      |
| weekly-review  | `0 16 * * 5`    | 4:00 PM Fridays only          |

## Required env vars on each routine

`ALPACA_API_KEY`, `ALPACA_SECRET_KEY`, `ALPACA_ENDPOINT`, `ALPACA_DATA_ENDPOINT`,
`PERPLEXITY_API_KEY`, `PERPLEXITY_MODEL`, `TELEGRAM_BOT_TOKEN`, `TELEGRAM_CHAT_ID`.

## Prereqs (one-time)

1. Install the Claude GitHub App on this repo.
2. Toggle **"Allow unrestricted branch pushes"** on each routine's environment.
3. Add env vars on each routine (NOT in a committed `.env`).

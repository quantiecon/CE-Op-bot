# Cloud Routines

Each `.md` file here is pasted verbatim into a Claude Code cloud routine's prompt
field. They are load-bearing — do not paraphrase. The env-var check block and the
commit-and-push step must survive intact or the bot silently fails.

## Schedule

Market opens 9:30 AM ET, closes 4:00 PM ET. Cron below is in America/Chicago.

| Routine        | Cron            | CT       | ET        | Rationale                          |
|----------------|-----------------|----------|-----------|------------------------------------|
| pre-market     | `0 8 * * 1-5`   | 8:00 AM  | 9:00 AM   | 30 min before bell — research/plan |
| market-open    | `0 9 * * 1-5`   | 9:00 AM  | 10:00 AM  | 30 min after bell — execute trades |
| midday         | `30 11 * * 1-5` | 11:30 AM | 12:30 PM  | mid-session check-in               |
| daily-summary  | `5 15 * * 1-5`  | 3:05 PM  | 4:05 PM   | 5 min after close — EOD snapshot   |
| weekly-review  | `0 16 * * 5`    | Fri 4 PM | Fri 5 PM  | end of trading week                |

## Required env vars on each routine

`ALPACA_API_KEY`, `ALPACA_SECRET_KEY`, `ALPACA_ENDPOINT`, `ALPACA_DATA_ENDPOINT`,
`PERPLEXITY_API_KEY`, `PERPLEXITY_MODEL`, `TELEGRAM_BOT_TOKEN`, `TELEGRAM_CHAT_ID`.

## Prereqs (one-time)

1. Install the Claude GitHub App on this repo.
2. Toggle **"Allow unrestricted branch pushes"** on each routine's environment.
3. Add env vars on each routine (NOT in a committed `.env`).

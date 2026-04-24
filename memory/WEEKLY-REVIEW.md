# Weekly Review

Friday reviews appended here.
Template for each entry:

## Week ending YYYY-MM-DD

### Stats
| Metric | Value |
|--------|-------|
| Starting portfolio | $X |
| Ending portfolio | $X |
| Week return | ±$X (±X%) |
| S&P 500 week | ±X% |
| Bot vs S&P | ±X% |
| Trades | N (W:X / L:Y / open:Z) |
| Win rate | X% |
| Best trade | SYM +X% |
| Worst trade | SYM -X% |
| Profit factor | X.XX |

### Closed Trades
| Ticker | Entry | Exit | P&L | Notes |

### Open Positions at Week End
| Ticker | Entry | Close | Unrealized | Stop |

### What Worked
- ...

### What Didn't Work
- ...

### Key Lessons
- ...

### Adjustments for Next Week
- ...

### Overall Grade: X

---

## Week ending 2026-04-24

### Stats
| Metric | Value |
|--------|-------|
| Starting portfolio | $100,000.00 |
| Ending portfolio | $100,010.17 |
| Week return | +$10.17 (+0.01%) |
| S&P 500 week | +0.24% |
| Bot vs S&P | -0.23% |
| Trades | 1 (W:0 / L:0 / open:1) |
| Win rate | N/A (0 closed) |
| Best trade | NVDA +2.51% (unrealized) |
| Worst trade | N/A |
| Profit factor | N/A (0 closed trades) |

### Closed Trades
| Ticker | Entry | Exit | P&L | Notes |
| — | — | — | — | No closed trades this week |

### Open Positions at Week End
| Ticker | Entry | Close | Unrealized | Stop |
| NVDA | $202.705 | $207.79 | +$10.17 (+2.51%) | $189.855 (trail 10%, GTC `4ad0c853`) |

### What Worked
- Infrastructure pipeline validated end-to-end: Alpaca order + trailing-stop GTC fired correctly on NVDA smoke test
- HOLD discipline on Day 1 — resisted FOMO into premarket gappers (INTC +24%, TXN +18%)
- Pre-market research logged before any trade decision
- Env-var + wrapper pattern worked cleanly; no direct curl calls

### What Didn't Work
- Bot launched Friday — effectively 1 trading day this week, no real research-driven exposure
- 99.6% cash at week end vs 75-85% deployed target (acceptable for Day 1, must fix next week)
- No sector-momentum entries into Energy despite XLE/XOM/CVX being on the shortlist
- Under-benchmarked S&P by 23 bps (trivial, but notable it was fixable with one XLE position)

### Key Lessons
- Launch-week cash drag is real; first real trading week (Apr 27-May 1) needs 2-3 sized entries to get deployed
- Smoke-test sizing (2 shares, 0.4% of portfolio) is fine to validate plumbing but shouldn't recur
- Friday pre-weekend + FOMC-next-week + Iran overhang was a legitimate HOLD context, not just cold feet

### Adjustments for Next Week
- Monday pre-market: commit to 1-2 research-driven entries from Energy leaders (XLE, XOM, CVX) on any dip
- Target 50%+ deployed by EOW (Fri May 1), building toward 75-85% by Week 3
- Stay inside 3 new trades/week cap; no make-up revenge trading from a flat first week
- FOMC mid-week — size entries pre-meeting, don't chase post-meeting ramp

### Overall Grade: B-
Clean infrastructure launch and correct HOLD discipline on a legitimately mixed tape, but the week is objectively incomplete — 1 day, 1 smoke-test trade, near-zero deployment. Grade reflects execution quality, not P&L.

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

---

## Week ending 2026-05-01

### Stats
| Metric | Value |
|--------|-------|
| Starting portfolio | $100,011.09 (Mon Apr 27 AM, = Apr 24 close) |
| Ending portfolio | $99,975.73 |
| Week return | -$35.36 (-0.04%) |
| S&P 500 week | +0.91% |
| Bot vs S&P | -0.95% |
| Trades | 1 (W:0 / L:0 / open:2) |
| Win rate | N/A (0 closed) |
| Best trade | XLE -0.10% (unrealized) |
| Worst trade | NVDA -2.21% (unrealized) |
| Profit factor | N/A (0 closed trades) |

### Closed Trades
| Ticker | Entry | Exit | P&L | Notes |
| — | — | — | — | No closed trades this week |

### Open Positions at Week End
| Ticker | Entry | Close | Unrealized | Stop |
| XLE | $58.85 | $58.79 | -$15.30 (-0.10%) | $53.8515 (trail 10%, GTC `a1f6efb3`, HWM $59.835) |
| NVDA | $202.705 | $198.22 | -$8.97 (-2.21%) | $195.138 (trail 10%, GTC `4ad0c853`, HWM $216.82) |

### What Worked
- Discipline on entry quality — XLE chosen over XOM (5% spread at open) for clean fill; sized exactly to 15% per rule
- Trailing-stop infrastructure flawless: both GTCs live, HWMs ratcheted appropriately, stops never within 3% of price
- Resisted FOMO despite under-deployment — no chase into NVDA pre-hyperscaler print, no chase into Energy at RSI >72
- Pre-market RESEARCH-LOG cadence recovered Wed-Fri after Mon-Tue gap; HOLD calls all justified by binary events (FOMC, Mag-4 AMC, AAPL, ISM)
- Sector thesis correct: Energy +22% YTD held leadership; UAE OPEC exit catalyst arrived as flagged

### What Didn't Work
- Mon-Tue research gap cost the week — no entries Mon/Tue/Wed meant Energy thesis only got 1 trading day of exposure (Thu) instead of 4
- Ended week at 15.4% deployed vs 75-85% target — second straight week badly under-deployed; cash drag is now structural, not launch-week
- XLE entry day (Thu) caught local high; -1.43% reversal Friday on UAE OPEC exit selling pressure (the catalyst we waited for hurt the position short-term)
- Only 1/3 weekly trade slots used despite multiple valid setups (XLB Materials never entered; XLE single-name ETF only)
- NVDA smoke-test position now -2.21% and clutter on the book; sub-sized at 0.4%, not worth managing but not stopped out

### Key Lessons
- Research cadence IS the strategy — the days we filed pre-market notes we acted; the days we didn't, we drifted. No exceptions.
- Waiting for binary-event clarity is correct, but "wait" must convert to "size" the next day or the cadence collapses into pure HOLD
- Sector momentum entries near RSI extremes need pullback patience — XLE at 72 RSI on Thu was already late; better fill would've been Mon/Tue dip
- Need a second uncorrelated leg (Materials/Industrials) to avoid single-sector concentration risk; one-position weeks underperform diversified weeks
- Smoke-test residue (NVDA 2 sh) should be closed once plumbing is validated; carrying it adds noise to P&L and management

### Adjustments for Next Week (May 4-8)
- Monday pre-market: file RESEARCH-LOG FIRST, then commit to 1 sector-leg entry (XLB Materials or fresh Energy add on dip) targeting 30%+ deployed by Tue close
- Push toward 60% deployed by EOW; the 75-85% band is a Week 3-4 target if research cadence holds
- Consider closing NVDA smoke-test position (2 sh, ~$396) — too small to manage, frees mental bandwidth and cleans up book
- Stay inside 3 trades/week cap; aim for 2-3 entries (Materials, second Energy add, optional Industrials) — no revenge trading from flat week
- Watch sector rotation: Tech still lagging YTD but month-to-date strong post-AAPL; if Tech base forms, one AI/semi entry permitted

### Overall Grade: C+
Week was a near-flat draw (-0.04%) while SPY booked +0.91% — bot underperformed the bench by 95 bps in a tape we should have caught at least half of. Execution improved late (XLE entry was clean, sized, stopped) but the 3-day Mon-Wed research gap and 15% deployment vs 75-85% target are the same Week 1 mistakes repeating. Grade reflects: discipline preserved (no rule violations, no FOMO, all stops live), but opportunity cost was real and the deployment gap is now a pattern, not a bug.

---

## Week ending 2026-05-08

### Stats
| Metric | Value |
|--------|-------|
| Starting portfolio | $99,961.93 (Mon May 4 AM) |
| Ending portfolio | $99,259.82 |
| Week return | -$702.11 (-0.70%) |
| S&P 500 week | +2.22% (SPX 7,228.38 → 7,388.66) |
| Bot vs S&P | -2.92% |
| Trades | 2 (closed:1L / new:1 / open at EOW:2) |
| Win rate | 0% (0W / 1 closed) |
| Best trade | NVDA (4 sh) +8.08% (unrealized) |
| Worst trade | XLE -5.26% (unrealized) |
| Profit factor | 0.00 (no closed winners; |loser| $15.39) |

### Closed Trades
| Ticker | Entry | Exit | P&L | Notes |
| NVDA (2 sh) | $202.705 (Apr 24) | $195.01 (May 4) | -$15.39 (-3.80%) | Smoke-test stop fired auto via GTC trail; clean execution, well inside -7% manual cut |

### Open Positions at Week End
| Ticker | Entry | Close | Unrealized | Stop |
| XLE | $58.85 | $55.7557 | -$789.05 (-5.26%) | $53.8515 (trail 10%, GTC `a1f6efb3`, HWM $59.835) |
| NVDA | $198.8925 | $214.96 | +$64.27 (+8.08%) | $196.02 (trail 10%, GTC `576ea764`, HWM $217.80) |

### What Worked
- Trailing-stop infrastructure proved itself again — NVDA smoke-test exited cleanly via GTC at $195.01, capping loss at -3.80% (well inside the -7% manual cut)
- Discipline on XLE through a sharp drawdown — held above pre-market exit triggers ($55.00 open, $54.73 30-min break) and never panic-cut despite -5% intraday Wed and oil-thesis breakdown
- NVDA stale 4-sh reload was handled correctly: trail attached immediately at open per Rule 4, position now +8.08% offsetting some XLE damage
- Pre-market RESEARCH-LOG cadence held all 5 days (Mon-Fri filed) — first full-week cadence streak; Wed/Thu logs correctly flagged broken energy thesis BEFORE drawdown deepened
- Recognized the NFP/PPI Friday risk and deferred new entries — preserved 2/3 weekly trade slots for Monday's post-print clarity

### What Didn't Work
- XLE single-position concentration meant the energy thesis breakdown (US-Iran production-easing consensus, WTI -7% to $93) drove almost the entire weekly P&L hit; no diversifying second-sector leg cushioned the move
- Despite 5 days of RESEARCH-LOG flagging XLB / XLI / QQQ as conditional adds, ZERO of those entries triggered — the conditional bar (SPX green + level break + volume) was met on at least Wed (post-tariff truce rally) but bot did not act
- Deployment stayed flat at 15.2% all week — third straight week well below 75-85% target; the gap is now structural, not a research-cadence problem
- Energy thesis was identifiably breaking by Tue (Saudi accelerating production) and confirmed broken by Wed (Brent -$10/day) — could have preemptively trimmed XLE before Thursday's slide rather than holding to test the manual-cut threshold
- Bot underperformed SPY by 292 bps in a clearly bullish tape (US-China tariff truce, +2.22% SPX week) — sat out the rally because the only deployed exposure was the wrong sector

### Key Lessons
- Single-position weeks are bet-the-farm weeks; even when the thesis is right (energy +22% YTD), one negative catalyst (US-Iran consensus) can erase the year's edge in 48 hours. A second uncorrelated leg is non-optional, not nice-to-have.
- Conditional entries with "if X then deploy" triggers must actually be acted on when X happens. Filing the plan but never pulling the trigger is functionally identical to no plan. The Wed tariff-truce rally was the trigger; bot was passive.
- Thesis-breaking news comes in stages: Saudi production chatter (Tue) → Brent dump (Wed) → WTI -7% (Thu). Waiting for the third confirmation costs 4-5% of entry. Two stages of breakage = preemptive trim, don't wait for stop.
- Friday weekly-cap discipline is fine, but holding 84.8% cash through a +2.22% SPX week is opportunity cost masquerading as patience. Patience > activity ≠ paralysis > underperformance.
- The daily-summary logs accurately diagnosed the bottleneck every day ("pre-market RESEARCH-LOG cadence the bottleneck"). When the bot KNOWS what's wrong and STILL doesn't fix it across 5 days, the rule needs operational teeth, not more diagnosis.

### Adjustments for Next Week (May 11-15)
- **Monday May 11 priority: resolve XLE.** If energy thesis remains broken (WTI < $95), exit preemptively at open rather than waiting for $54.73 manual cut or $53.85 trail; redeploy ~$14k freed cash into XLB or XLI same-day on confirmation.
- Commit to TWO sector-momentum entries Monday-Tuesday (XLB Materials + XLI Industrials, or one of them + a tech-rotation leg via QQQ) — target 45%+ deployed by Tue close, 60%+ by EOW.
- Conditional entries from RESEARCH-LOG must convert to orders the same session the trigger fires; if SPX is green and target ETF clears its level on volume, ENTER. No more "carryover idea (untriggered N sessions)" entries.
- CPI May 12 (Tue) + PPI May 13 (Wed) = the week's binary risk. Defer the SECOND entry until post-CPI tape clarity; FIRST entry can size pre-CPI on a cool-print bias if leadership holds.
- Rule 10 tracker: if XLE exits red Monday, energy sector hits its first failed trade (NVDA smoke-test was tech, doesn't count). One more failed energy trade = sector cooldown per rule 10 — be selective on any future energy reentry.

### Overall Grade: C-
Bot lost -0.70% in a +2.22% SPY week — relative underperformance of 292 bps, the worst gap of the phase. Discipline preserved (no rule violations, all stops live, RESEARCH-LOG cadence held all 5 days, NVDA stop-out clean), but the same three structural issues compounded: single-position concentration, 15% deployment vs 75-85% target, and conditional-entry plans that never got pulled. The grade is one notch below last week because the cost of the deployment gap is no longer abstract — it's now -2.92% vs benchmark in a week SPY ran +2.22%. Discipline without deployment is hibernation. Next week must prove the bot can convert filed conditional entries into actual orders.

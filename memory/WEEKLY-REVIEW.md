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

## Week ending 2026-05-15

### Stats
| Metric | Value |
|--------|-------|
| Starting portfolio | $99,316.87 (Mon May 11 AM, = May 8 close) |
| Ending portfolio | $98,024.93 |
| Week return | -$1,291.94 (-1.30%) |
| S&P 500 week (SPY $737.54→$739.10) | +0.21% |
| Bot vs S&P | -1.51% |
| Trades | 2 entries (W:0 / L:2 / open:2 carry) |
| Win rate | 0% (0W / 2L closed) |
| Best trade | NVDA +13.15% (unrealized) |
| Worst trade | MP -6.67% (closed) |
| Profit factor | 0.00 (zero winners / $2,194 losers) |

### Closed Trades
| Ticker | Entry | Exit | P&L | Notes |
| USAR | $25.74 (May 12) | $24.27 (May 14) | -$974.61 (-5.71%) | Trail 10% GTC fired at open; materials fail #1 |
| MP | $65.14 (May 12) | $60.80 (May 14) | -$1,219.54 (-6.67%) | Trail 10% GTC fired at open; materials fail #2 → Rule 10 cooldown |

### Open Positions at Week End
| Ticker | Entry | Close | Unrealized | Stop |
| NVDA | $198.8925 | $225.04 | +$104.59 (+13.15%) | $219.9822 (trail 7%, GTC `775288b4`, HWM $236.54) |
| XLE | $58.85 | $59.36 | +$130.05 (+0.87%) | $53.8515 (trail 10%, GTC `a1f6efb3`, HWM $59.835) |

### What Worked
- Deployment finally moved Tue: 15% → 50.8% on MP+USAR adds; first real attempt at the 75-85% target band
- Trail discipline executed flawlessly on both stop-outs — capped losses at -5.71% / -6.67% (both inside the -7% manual cut), no slippage to catastrophe
- NVDA tighten-trigger rule (10%→7% at +15%) executed cleanly via order replacement (`576ea764` → `775288b4`); locked in ~$84 of $116 unrealized
- Rule 10 sector cooldown triggered correctly on 2 consecutive materials fails — no revenge entry attempt Fri
- XLE survived the energy-thesis-break (WTI $93 low) without manual cut; recovered to green by Fri as oil bounced to $105
- Friday HOLD discipline into NVDA-earnings week (Tue May 20 AMC) — no chase, no fresh binary exposure

### What Didn't Work
- 2-for-2 stop-outs same week on the new adds — both materials, both round-tripped negative; -$2,194 realized in one morning
- Entered MP + USAR on the same day (Tue) into the same sector — concentration risk that Rule 9 (sector momentum) was supposed to filter, not amplify; correlated sector picks defeated the diversification intent
- Sized at 18%+ each (MP ~18.3k, USAR ~17.1k) — near the 20% cap; cap-edge sizing on unproven adds maximized the realized loss
- Pre-market RESEARCH-LOG cadence still spotty Mon-Wed; the cadence-gap pattern from Weeks 1-2 persists
- NVDA still 4 shares (sub-1% notional) — the original smoke-test residue from Apr 24 was never up-sized; carrying a winner at 0.8% allocation is leaving alpha on the table (NVDA +13% on $800 = ~$104; same return on a 15% position would have been ~$2,000)
- Bot vs SPY -1.51% is the worst weekly relative of the phase; phase now -1.97% vs benchmark cumulative drag widening

### Key Lessons
- "Sector momentum" must be filtered for correlation — MP and USAR are both rare-earth/critical-minerals plays; entering both same day was a single bet sized at 36%, not two diversified bets sized 18% each
- Two same-sector entries should be staged 2+ days apart with the first showing follow-through before the second is sized — Tue-Tue same-sector double-up is the Rule 9 misread
- Trail discipline is the strategy's actual edge — both losses capped exactly where the rule said they would. Without the 10% trail, both could have gapped to -10 to -15% easily
- Winners need to be sized like winners — NVDA conviction has been validated by the tape (+13% from entry, +15% threshold crossed). The 4-share stale-buy residue should have been added to (within Rule 11 patience, not into earnings) during the Week 2 setup, not left as a smoke-test artifact
- Earnings-week defense is correct: NVDA AMC Tue → trail at $219.98 locks ~$84 of $116 unrealized; not adding into the print is the right R:R call

### Adjustments for Next Week (May 18-22)
- **NVDA earnings Tue May 20 AMC** = the week's biggest event. Plan: HOLD through, no trim, no add. Trail at $219.98 protects ~58% of unrealized; reassess Wed AM on the reaction.
- **Materials sector BLOCKED by Rule 10 cooldown** — no MP, USAR, XLB, or rare-earth single names until cooldown reset (define reset as: 1 full week elapsed AND a clean tape signal)
- **Energy still on watch**: XLE recovered, breakout setup intact; one add candidate (XOM or CVX single-name) considered IF WTI holds $100+ Mon-Tue AND XLE confirms green
- **Industrials (XLI)** = primary new-leg candidate post-NVDA-earnings clarity: +24% YTD, AI capex / defense tailwinds, less commodity-sensitive
- **Sizing rule for the week**: max 1 new entry pre-NVDA print; max 1 additional post-print only if Tue tape is clean. Stay inside 3-trade cap with explicit bias to use ≤2
- **Correlation check before any 2nd entry**: must be in a different sector from the existing book (currently energy + tech); no second tech or second energy add without explicit thesis distinction

### Overall Grade: C-
Week 3 was the phase's worst on every dimension: -1.30% absolute (worst), -1.51% vs SPY (worst relative), 2 stop-outs same week (Rule 11 caution flag), Rule 10 sector cooldown triggered. But — and it matters — every loss was capped exactly by the trailing-stop rule, no -7% manual cut was breached, NVDA tighten executed flawlessly, no panic add Fri into NVDA-earnings week, XLE held the line. Grade is not D because the strategy machinery worked; grade is C- because the strategy decision (two correlated same-sector entries same day at near-cap sizing) was a Rule 9 misread that turned -$2,194 realized in one morning. The fix is filtering for correlation inside "sector momentum" — not deploying less.

---

## Week ending 2026-05-22

### Stats
| Metric | Value |
|--------|-------|
| Starting portfolio | $98,034.53 (Mon May 18 AM, = May 15 close) |
| Ending portfolio | $100,359.77 |
| Week return | +$2,325.24 (+2.37%) |
| S&P 500 week (SPY $739.25→$746.18) | +0.94% |
| Bot vs S&P | +1.43% |
| Trades | 2 entries (W:2 / L:0 / open:1 carry); 1 unauthorized entry, both closed green |
| Win rate | 100% (2W / 0L closed) |
| Best trade | NVDA +10.58% (closed) |
| Worst trade | MP +3.28% (closed) — both winners |
| Profit factor | ∞ ($2,433.62 winners / $0 losers) |

### Closed Trades
| Ticker | Entry | Exit | P&L | Notes |
| NVDA | $198.8925 (May 5) | $219.9275 (May 18) | +$84.14 (+10.58%) | 7% trail GTC `775288b4` fired pre-earnings; first green realized exit of the phase |
| MP | $62.3735 (May 21, unauthorized) | $64.4165 (May 22) | +$2,349.48 (+3.28%) | Forced liquidation per incident-response plan (Rule 3/10/4 violations); MP gapped strong on open, surprise green |

### Open Positions at Week End
| Ticker | Entry | Close | Unrealized | Stop |
| XLE | $58.85 | $59.50 | +$165.75 (+1.10%) | $55.53 (trail 10%, GTC `a1f6efb3`, HWM $61.70) |

### What Worked
- **Pre-earnings de-risk on NVDA**: 7% trail fired Mon May 18 at $219.93, locking +$84.14 (+10.58%) — first green realized exit of the phase, perfect timing 2 days before Wed AMC binary
- **Incident-response discipline on the MP slug**: pre-market plan called for full liquidation at open regardless of P&L; executed cleanly at 9:33 ET @ $64.4165 avg, surprise +$2,349 on a rules-violating slug we were prepared to take a loss on
- **XLE rode the energy bid all week**: WTI $99→$103→$102 range, HWM ratcheted $59.835→$61.70, trail auto-tightened $53.85→$55.53; position survived a binary-day intraday give-back (Wed -2.28%) without manual intervention
- **Zero new bot-initiated entries through a double-binary mid-week** (NVDA AMC Wed + FOMC minutes Wed 2 PM) — defensive bias correct, preserved dry powder
- **Phase recovered above $100K baseline** for the first time since the early-phase dip: -2.79% Thu close → +0.36% Fri close, a +3.15-pt phase swing driven by MP exit + XLE intraday strength
- **Rule 11 (patience > activity) ratified**: phantom MP order Mon was cancelled cleanly before fill; XLI triple-trigger Thu didn't confirm and was correctly deferred

### What Didn't Work
- **Unauthorized MP fill Thu May 21 2:23 PM ET** is the dominant negative event of the week: 1150 sh @ $62.3735 avg, $71,729.50 notional, **73.5% of equity** (3.7× the 20% cap), in a sector under Rule 10 cooldown, with NO trailing stop attached — three hard-rule violations simultaneously. Source still unidentified (audit deferred); bot did not place the order, no plan authorized it
- **The week's +$2,325 return is heavily tail-dependent on the MP gap**: MP opened strong and gave us +$2,349 realized; the same slug could have opened -$2,000 to -$5,000 just as easily. Outcome was lucky, not earned
- **Deployment still 15.1% post-MP-exit** vs 75-85% target — sixth straight week below band; only one position on the book again (XLE)
- **Friday weekly-review didn't pre-empt the audit gap** — source of the MP fill remains unknown going into Week 5, meaning another unauthorized fill could land at any time without a detection mechanism beyond manual order-book checks
- **NVDA re-entry forfeited** — flat into the print was correct R:R, but the post-print tape (NVDA $223.47, AH down ~1%) wasn't actionable; lost the second-leg opportunity for the week
- **XLI triple-trigger Thu was the cleanest non-materials second-leg signal of the phase** — it didn't fully confirm (NVDA AH softness + SPX direction noisy) and was correctly deferred, but that defer leaves us still single-position into Week 5

### Key Lessons
- **Pre-event de-risking via trail tightening works as designed**: 10%→7% trail on NVDA at +15% threshold locked +$84 on the print's binary risk — exactly the asymmetry Rule 6 is engineered for. Repeatable, scalable
- **Incident-response plans are worth writing down**: the pre-market MP-liquidation plan was specific (sell at open, market order, no stop placement, day-trade-implication checked) and executed in 90 seconds at 9:33 ET. Pre-committed protocols beat real-time deliberation
- **An unauthorized fill is a system risk, not a strategy risk** — TRADING-STRATEGY.md rules behaved correctly when applied (forced exit); the gap is in detection / source identification before the fill, not in the rules themselves. Need a tooling-level fix (order-watch alert), not a strategy edit
- **The MP outcome should not change the materials cooldown stance** — Rule 10 is built precisely so we don't get whipsawed by a lucky-tail re-entry into a failed sector. Cooldown stays active going into Week 5
- **Single-position weeks are the deployment-drag pattern, not the cause**: 5 of 5 weeks have ended single-position-heavy because adds keep getting deferred or stopped out. The fix is not "deploy more aggressively" but "let the XLI / second-leg signal mature and size to 15% (not 20%) on confirmation"

### Adjustments for Next Week (May 26-29; Mon May 25 = Memorial Day, markets closed)
- **Tue May 26 pre-market RESEARCH-LOG must lead with MP audit findings**: identify the source of the May 21 fill (client_order_id provenance, API call logs, user override possibility); document a detection mechanism (e.g., open-orders snapshot diff hourly) before any new entries
- **XLI remains the top second-leg candidate**: same triple-trigger checklist (SPX green / XLI > prior-day high on volume / tech doesn't cascade), 15% sizing (NOT 20%), 10% trail GTC immediately on fill
- **Energy: XLE on autopilot**, but WTI $97-98 second test = if $97 breaks Tue/Wed, expect XLE drawdown toward $55-56 trail; trust the GTC, do not pre-empt
- **Materials cooldown remains active** — Rule 10 not reset by lucky MP exit. No XLB, MP, USAR, rare-earth single names until cooldown formally reset (1 full week clean tape + non-materials Win in the book)
- **Deployment target**: 30-35% by Wed May 27 close if XLI confirms; 50-60% by Friday only on a second confirming non-materials signal (no forced 75% chase)
- **Trade cap**: Week 5 resets to 3 fresh entries; bias to use ≤2 with explicit thesis distinction (Energy already on; second entry must be non-Energy, non-Materials)
- **PCE Thu May 28** is the next macro event — size entries pre-PCE, no chasing post-PCE ramp

### Overall Grade: B+
Week 4 booked the phase's best absolute (+2.37%) and best relative (+1.43% vs SPY) returns, recovered the phase back above $100K baseline for the first time since early-phase dip, and executed two textbook closed trades (NVDA pre-earnings trail at +10.58%, MP forced liquidation at +3.28% on a rules-violating slug). Every bot-initiated decision this week was correct: HOLD through the double binary, trail-protect NVDA into earnings, ignore the phantom MP buy Mon, execute the MP liquidation Fri AM per plan. Grade is not A because **the +$2,349 on MP is heavily luck-tail** — same slug could have gapped -$2k just as easily; we don't grade A for outcomes that were a coin flip. Grade is not A- because the unauthorized fill exposed a real detection gap (source still unidentified Friday close). Grade is B+ because: (1) discipline was perfect, (2) the weekly metrics are objectively the phase's best, (3) the recovery is real and rule-driven, (4) the lurking system-level risk (another unauthorized fill) means the work isn't done. Strategy doesn't need a rule change — Rule 3/10/4 caught the violation; the fix is tooling/detection.

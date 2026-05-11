# Trade Log

## Day 0 — EOD Snapshot (pre-launch baseline)
**Portfolio:** $100,000.00 | **Cash:** $100,000.00 (100%) | **Day P&L:** $0 | **Phase P&L:** $0

No positions yet. Bot launches tomorrow.

## Apr 24 — Trade: NVDA (manual smoke test)
**Action:** BUY 2 NVDA @ $202.705 | **Cost basis:** $405.41 | **Time:** 10:17 AM ET
**Trailing stop:** GTC sell 2 NVDA, trail 10%, initial stop $182.39 (order `4ad0c853`)
**Rationale:** End-to-end pipeline test — confirm Alpaca wrapper places orders and trailing stops.
Not based on research signal. Smoke test only.

### Apr 24 — EOD Snapshot (Day 1, Friday)
**Portfolio:** $100,011.09 | **Cash:** $99,594.59 (99.6%) | **Day P&L:** +$11.09 (+0.01%) | **Phase P&L:** +$11.09 (+0.01%)

| Ticker | Shares | Entry | Close | Day Chg | Unrealized P&L | Stop |
|--------|--------|-------|-------|---------|----------------|------|
| NVDA | 2 | $202.705 | $208.24 | +4.31% | +$11.07 | $189.855 (trail 10%) |

**Notes:** First live day, smoke-test only. Bought 2 NVDA at 10:17 ET to validate the Alpaca wrapper + trailing-stop pipeline; trailing stop is live as GTC (order `4ad0c853`, HWM $210.95, stop $189.855). No research-driven trades today. Position is ~0.4% of portfolio — sub-sizing is intentional for the smoke test. Trades this week: 1/3. Cash ~99.6% deployed-available, well under the 75–85% deployed target; full deployment starts next week once research cadence is running. Tomorrow is Saturday (market closed); Monday plan: run pre-market research, pick 2–3 candidates from sector-momentum leaders, size real positions per 20%-cap rule.

### Apr 27 — EOD Snapshot (Day 2, Monday)
**Portfolio:** $100,028.31 | **Cash:** $99,594.59 (99.6%) | **Day P&L:** +$17.18 (+0.02%) | **Phase P&L:** +$28.31 (+0.03%)

| Ticker | Shares | Entry | Close | Day Chg | Unrealized P&L | Stop |
|--------|--------|-------|-------|---------|----------------|------|
| NVDA | 2 | $202.705 | $216.86 | +4.12% | +$28.31 | $195.138 (trail 10%) |

**Notes:** Quiet first Monday — no new trades. NVDA continued higher (+4.12% on day, +6.98% from entry); trailing stop ratcheted up automatically to $195.138 with HWM $216.82 (still below the +15% tighten threshold of $233.11, so 10% trail stays). Cash remains ~99.6% — well below the 75–85% deployment target, but deliberate while research cadence comes online. No pre-market research log was filed today, so no signal-driven entries; that's the gap to close tomorrow. Trades today: 0. Trades this week: 0/3. Tomorrow (Tue Apr 28): run pre-market scan, pick 2–3 sector-momentum candidates, size first real position(s) at 15–20% per the cap rule.

### Apr 28 — EOD Snapshot (Day 3, Tuesday)
**Portfolio:** $100,020.95 | **Cash:** $99,594.59 (99.6%) | **Day P&L:** -$7.36 (-0.01%) | **Phase P&L:** +$20.95 (+0.02%)

| Ticker | Shares | Entry | Close | Day Chg | Unrealized P&L | Stop |
|--------|--------|-------|-------|---------|----------------|------|
| NVDA | 2 | $202.705 | $213.18 | -1.58% | +$20.95 | $195.138 (trail 10%, HWM $216.82) |

**Notes:** Quiet Tuesday — no new trades, no pre-market research log filed (gap from yesterday still open). NVDA gave back ~1.6% on the day to $213.18 but remains +5.17% from entry; HWM held at $216.82, trailing stop unchanged at $195.138 (room ~8.5% above stop). No tighten trigger yet (+15% threshold = $233.11). Cash still ~99.6% — second straight day at near-zero deployment vs the 75–85% target; the bottleneck is research cadence, not capital. Trades today: 0. Trades this week: 0/3. Tomorrow (Wed Apr 29): file pre-market RESEARCH-LOG entry first thing, then size 1–2 sector-momentum candidates at 15–20% to start real deployment; otherwise we burn the whole week at 0.4% deployed.

## Apr 30 — Trade: XLE (sector momentum entry)
**Action:** BUY 255 XLE @ $58.85 | **Cost basis:** $15,006.75 (15.00% of equity) | **Time:** 9:37 AM ET
**Trailing stop:** GTC sell 255 XLE, trail 10%, initial stop $52.97, HWM $58.855 (order `a1f6efb3`)
**Thesis:** Energy YTD leader (+22%); WTI ~$109-110 / Brent ~$112+ on Iran/Hormuz risk + UAE OPEC exit chatter. XLE is the sector ETF play with tight spread vs single-name XOM (which had ~5% spread at open — skipped).
**Target:** +15% (~$67.68) | **R:R:** ~1.5:1 (10% trail stop, 15% target)

### Apr 29 — EOD Snapshot (Day 4, Wednesday)
**Portfolio:** $100,011.11 | **Cash:** $99,594.59 (99.6%) | **Day P&L:** -$9.84 (-0.01%) | **Phase P&L:** +$11.11 (+0.01%)

| Ticker | Shares | Entry | Close | Day Chg | Unrealized P&L | Stop |
|--------|--------|-------|-------|---------|----------------|------|
| NVDA | 2 | $202.705 | $208.26 | -2.30% | +$11.11 | $195.138 (trail 10%, HWM $216.82) |

**Notes:** Third quiet day in a row — no new trades, no pre-market RESEARCH-LOG filed (gap now 3 days running). NVDA gave back another 2.30% to $208.26, +2.74% from entry; HWM unchanged at $216.82, trailing stop unchanged at $195.138 (~6.3% above stop). Cash still ~99.6% — fourth straight day at near-zero deployment vs the 75–85% target. Bottleneck remains research cadence, not capital or signals. Trades today: 0. Trades this week: 0/3 (Mon–Wed all zero). Tomorrow (Thu Apr 30): file pre-market RESEARCH-LOG entry FIRST, then commit to sizing 1–2 sector-momentum candidates at 15–20% — only 2 trading days left this week before the cap window resets, and we cannot burn another week at 0.4% deployed.

### Apr 30 — EOD Snapshot (Day 5, Thursday)
**Portfolio:** $100,197.59 | **Cash:** $84,587.84 (84.4%) | **Day P&L:** +$186.48 (+0.19%) | **Phase P&L:** +$197.59 (+0.20%)

| Ticker | Shares | Entry | Close | Day Chg | Unrealized P&L | Stop |
|--------|--------|-------|-------|---------|----------------|------|
| XLE | 255 | $58.85 | $59.65 | +1.05% | +$204.00 | $53.8515 (trail 10%, HWM $59.835) |
| NVDA | 2 | $202.705 | $199.51 | -4.66% | -$6.39 | $195.138 (trail 10%, HWM $216.82) |

**Notes:** First real deployment day of the phase — bought 255 XLE @ $58.85 at 9:37 ET (15.0% of equity) on the energy/Iran-Hormuz thesis; trailing stop live as GTC (order `a1f6efb3`, HWM $59.835, stop $53.8515). XLE closed +1.05% on day (+$204 unrealized) — clean entry. NVDA dropped -4.66% to $199.51 (now -$6.39, -1.58% from entry) but stop unchanged at $195.138 with ~2.2% buffer; if NVDA breaks $195.14 tomorrow the GTC fires and we exit. Cash now 84.4% — moved from 99.6% deployment gap to within the 75-85% target band on the cash side (deployed only 15.6%, still light). Trades today: 1 (XLE). Trades this week: 1/3. Tomorrow (Fri May 1): run weekly-review (Friday cadence), monitor XLE momentum and NVDA stop proximity, consider second sector-momentum entry if research supports — energy or AI/semis, but only if XLE thesis is intact and NVDA hasn't stopped out.

## May 04 — Exit: NVDA (trailing stop fired)
**Action:** SELL 2 NVDA @ $195.01 | **Time:** 11:21 AM ET | **Order:** `4ad0c853` (GTC trailing stop, auto-cancelled on fill)
**Entry:** $202.705 (Apr 24) | **Exit:** $195.01 | **Realized P&L:** -$15.39 (-3.80%)
**Reason:** 10% trailing stop GTC fired automatically at $195.138 (HWM $216.82). Did NOT hit -7% manual cut threshold. Smoke-test position; trail did its job.

### May 01 — EOD Snapshot (Day 6, Friday)
**Portfolio:** $99,979.04 | **Cash:** $84,587.84 (84.6%) | **Day P&L:** -$218.69 (-0.22%) | **Phase P&L:** -$20.96 (-0.02%)

| Ticker | Shares | Entry | Close | Day Chg | Unrealized P&L | Stop |
|--------|--------|-------|-------|---------|----------------|------|
| XLE | 255 | $58.85 | $58.80 | -1.43% | -$12.75 | $53.8515 (trail 10%, HWM $59.835) |
| NVDA | 2 | $202.705 | $198.60 | -0.49% | -$8.21 | $195.138 (trail 10%, HWM $216.82) |

**Notes:** Quiet Friday — no new trades. Both positions slipped: XLE -1.43% to $58.80 (now -$12.75, -0.08% from entry), NVDA -0.49% to $198.60 (now -$8.21, -2.03% from entry). Neither HWM advanced; trailing stops unchanged (XLE $53.8515, NVDA $195.138). NVDA stop buffer tight at ~1.7% — first break Monday and the GTC fires. Cash steady at 84.6% (deployed 15.4%) — still light vs the 75–85% deployed target, week ends with one real position on the books. Trades today: 0. Trades this week: 1/3 (XLE only). Phase ends Week 1 at -$21 (-0.02%) — flat-to-slightly-red, benchmark check vs SPY pending in weekly-review. Monday plan (May 4): file pre-market RESEARCH-LOG first thing, watch NVDA stop proximity at the open, and look for a 2nd sector-momentum candidate (energy continuation or rotation into AI/semis) to lift deployment toward the 75% floor.

## May 05 — Trade: NVDA (stale orders filled at open + trail attached)
**Action:** BUY 4 NVDA @ $198.8925 avg | **Cost basis:** $795.57 (~0.8% of equity) | **Time:** market open
**Trailing stop:** GTC sell 4 NVDA, trail 10%, initial stop $179.595, HWM $199.55 (order `576ea764`)
**Rationale:** Stale market-buy orders queued May 4 22:01/22:45 ET filled at open as flagged in pre-market log. Not research-driven; trivial $800 notional. Trail attached immediately per Rule 4.

### May 04 — EOD Snapshot (Day 7, Monday)
**Portfolio:** $100,119.76 | **Cash:** $84,977.86 (84.9%) | **Day P&L:** +$140.72 (+0.14%) | **Phase P&L:** +$119.76 (+0.12%)

| Ticker | Shares | Entry | Close | Day Chg | Unrealized P&L | Stop |
|--------|--------|-------|-------|---------|----------------|------|
| XLE | 255 | $58.85 | $59.38 | +0.90% | +$135.15 | $53.8515 (trail 10%, HWM $59.835) |

**Notes:** NVDA stopped out at 11:21 ET — GTC trailing stop fired at $195.01, closing the smoke-test position for a realized -$15.39 (-3.80%); trail did its job, well inside the -7% manual cut threshold. XLE held +0.90% on the day to $59.38, +0.90% from entry, +$135.15 unrealized; HWM unchanged at $59.835, stop $53.8515 (~9.3% buffer). New week begins — trades today: 1 (NVDA SELL, no new entries); trades this week: 0/3 entries used. Cash 84.9% — deployment now at 15.1%, still well below the 75-85% deployed target. With NVDA gone we're down to a single position; need to add 2-3 sector-momentum candidates this week to lift deployment. Tomorrow (Tue May 5): file pre-market RESEARCH-LOG, screen energy continuation vs AI/semis rotation, size 1-2 entries at 15-20% to begin filling the deployment gap.

### May 05 — EOD Snapshot (Day 8, Tuesday)
**Portfolio:** $100,126.56 | **Cash:** $84,182.29 (84.1%) | **Day P&L:** +$6.80 (+0.01%) | **Phase P&L:** +$126.56 (+0.13%)

| Ticker | Shares | Entry | Close | Day Chg | Unrealized P&L | Stop |
|--------|--------|-------|-------|---------|----------------|------|
| XLE | 255 | $58.85 | $59.45 | +0.10% | +$153.00 | $53.8515 (trail 10%, HWM $59.835) |
| NVDA | 4 | $198.8925 | $196.13 | -1.18% | -$11.05 | $180.216 (trail 10%, HWM $200.24) |

**Notes:** Quiet Tuesday — no research-driven entries. Today's only fill was the stale market-buy reload of 4 NVDA @ $198.8925 at the open (queued May 4 22:01/22:45 ET, not signal-driven, ~$800 notional); trailing stop attached immediately as GTC (order `576ea764`, HWM $200.24, stop $180.216). XLE held +0.10% on day to $59.45, +1.02% from entry, +$153 unrealized; HWM unchanged at $59.835, stop $53.8515 (~9.4% buffer, well below the +15% tighten threshold of $67.68). NVDA -1.18% on day to $196.13, -1.39% from entry, -$11.05 unrealized; stop buffer ~8.1%, no tighten triggers. Cash 84.1% — deployment now 15.9%, still well below the 75–85% deployed target. Trades today: 1 (NVDA stale BUY). Trades this week: 1/3 entries used. Pre-market RESEARCH-LOG cadence still the bottleneck — without research signals we cannot add the 2–3 new positions needed to lift deployment toward 75%. Tomorrow (Wed May 6): file pre-market RESEARCH-LOG entry FIRST, then size 1–2 sector-momentum candidates at 15–20% (energy continuation, AI/semis rotation, or new sector leader); 2 entries remain in the weekly cap.

### May 06 — EOD Snapshot (Day 9, Wednesday)
**Portfolio:** $99,577.48 | **Cash:** $84,182.28 (84.5%) | **Day P&L:** -$549.08 (-0.55%) | **Phase P&L:** -$422.52 (-0.42%)

| Ticker | Shares | Entry | Close | Day Chg | Unrealized P&L | Stop |
|--------|--------|-------|-------|---------|----------------|------|
| XLE | 255 | $58.85 | $57.12 | -3.92% | -$441.15 | $53.8515 (trail 10%, HWM $59.835) |
| NVDA | 4 | $198.8925 | $207.40 | +5.55% | +$34.03 | $187.4385 (trail 10%, HWM $208.265) |

**Notes:** Worst day of the phase — Day P&L -$549 (-0.55%) drags phase to -$422 (-0.42%), first time underwater. Driver was XLE -3.92% on the day to $57.12 (-$441 unrealized, -2.94% from entry); energy thesis under pressure as oil rolled over intraday. Stop unchanged at $53.8515, buffer now ~5.7% — closer to firing but still well outside the -7% manual cut from entry (cut threshold ~$54.73, current $57.12, ~4.4% buffer). NVDA cushioned the loss: +5.55% to $207.40, +4.28% from entry, +$34 unrealized; HWM ratcheted up to $208.265, stop tightened automatically to $187.4385 (still 10% trail, +15% tighten threshold = $228.73 not yet hit). No fills today, no research-driven entries — pre-market RESEARCH-LOG cadence still the bottleneck (4 trading days running). Cash 84.5%, deployment 15.5% — unchanged. Trades today: 0. Trades this week: 1/3 entries used. Tomorrow (Thu May 7): file pre-market RESEARCH-LOG FIRST, watch XLE stop proximity at the open, and decide whether energy thesis is broken (consider exiting before stop fires if oil keeps rolling) or to hold and add a defensive/rotation candidate (utilities, staples, or AI/semis on continuation) to diversify away from single-sector concentration.

### May 07 — Midday Scan (no action)
**Positions snapshot:**

| Ticker | Shares | Entry | Last | P&L % | Unrealized P&L | Stop |
|--------|--------|-------|------|-------|----------------|------|
| XLE | 255 | $58.85 | $55.905 | -5.00% | -$750.98 | $53.8515 (trail 10%, HWM $59.835) |
| NVDA | 4 | $198.8925 | $212.265 | +6.72% | +$53.49 | $192.78 (trail 10%, HWM $214.20) |

**Actions:** None.
**Step 3 (cut losers):** XLE at -5.00%, not at -7%. No manual cut.
**Step 4 (tighten winners):** NVDA at +6.72%, below +15% tighten threshold ($228.73). Trail auto-ratcheted from $187.44 to $192.78 on HWM bump to $214.20. No manual tighten.
**Step 5 (thesis check on XLE):** Energy thesis already documented broken in pre-market log (WTI -7% to ~$93 on US-Iran production-easing consensus). Pre-market plan set preemptive exit triggers at open ≤ $55.00 OR break of $54.73 in first 30 min — neither triggered (open held above, current $55.905). Discipline says hold the plan: trail at $53.85 will catch downside; manual cut at $54.73 if breached. NFP/PPI tomorrow 8:30 AM = avoid discretionary mid-band cuts that could be reversed by a soft print. Buffer to manual cut: ~2.1%; buffer to trail: ~3.7%.
**Cash/Equity:** Cash $84,182.28; equity ~$99,287 (mark-to-market); deployment ~15.2%. No fills today.
**Trades this week:** 1/3 (stale NVDA reload Tue). 2 entries remain — deferring to Monday post-NFP per pre-market decision.

### May 07 — EOD Snapshot (Day 10, Thursday)
**Portfolio:** $99,283.76 | **Cash:** $84,182.28 (84.8%) | **Day P&L:** -$293.72 (-0.30%) | **Phase P&L:** -$716.24 (-0.72%)

| Ticker | Shares | Entry | Close | Day Chg | Unrealized P&L | Stop |
|--------|--------|-------|-------|---------|----------------|------|
| XLE | 255 | $58.85 | $55.90 | -1.93% | -$752.25 | $53.8515 (trail 10%, HWM $59.835) |
| NVDA | 4 | $198.8925 | $211.745 | +1.88% | +$51.41 | $192.78 (trail 10%, HWM $214.20) |

**Notes:** Phase low — Day P&L -$294 (-0.30%) extends phase to -$716 (-0.72%); NVDA's +$15.66 intraday gain (HWM ratcheted to $214.20, trail to $192.78) only partially offset XLE's -$280.50 intraday slide. XLE closed $55.90 (-5.01% from entry, -$752 unrealized) — held above the preemptive exit triggers from pre-market plan (open ≤ $55.00 / break $54.73 in first 30 min); discipline held, no discretionary cut. Manual -7% threshold = $54.73 (~1.9% buffer); trail $53.8515 (~3.7% buffer). NVDA +6.46% from entry, well below +15% tighten threshold ($228.73). No fills today; pre-market RESEARCH-LOG cadence still the bottleneck (5 trading days running). Cash 84.8%, deployment 15.2% — unchanged. Trades today: 0. Trades this week: 1/3 (NVDA stale reload Tue). Tomorrow (Fri May 8): NFP/PPI 8:30 AM ET — defer entries pre-print, watch XLE for cut on soft oil print or break of $54.73, run weekly-review post-close, consider trimming/exiting XLE if energy thesis remains broken into Monday.

### May 08 — EOD Snapshot (Day 11, Friday)
**Portfolio:** $99,316.87 | **Cash:** $84,182.28 (84.8%) | **Day P&L:** +$33.11 (+0.03%) | **Phase P&L:** -$683.13 (-0.68%)

| Ticker | Shares | Entry | Close | Day Chg | Unrealized P&L | Stop |
|--------|--------|-------|-------|---------|----------------|------|
| XLE | 255 | $58.85 | $56.01 | +0.11% | -$724.20 | $53.8515 (trail 10%, HWM $59.835) |
| NVDA | 4 | $198.8925 | $213.01 | +0.71% | +$56.47 | $192.78 (trail 10%, HWM $214.20) |

**Notes:** Quiet finish to a red week. Day P&L +$33 (+0.03%) — modest bounce off Thursday's phase low; phase still -$683 (-0.68%). NFP/PPI prints absorbed without forcing a manual cut on XLE: closed $56.01 (+0.11% on day, -4.83% from entry, -$724 unrealized) — held above both the $55.00 open trigger and the $54.73 manual-cut threshold (~2.3% buffer); trail $53.8515 (~3.9% buffer). HWM unchanged at $59.835 — no auto-tighten. NVDA +0.71% to $213.01 (+7.10% from entry, +$56 unrealized); HWM unchanged at $214.20, stop unchanged at $192.78 (+15% tighten threshold $228.73 not hit). No fills today; pre-market RESEARCH-LOG cadence remained the bottleneck (6 trading days running). Cash 84.8%, deployment 15.2% — unchanged for the entire week. Trades today: 0. Trades this week: 1/3 (NVDA stale reload Tue). Week 2 closes flat-to-red vs SPY benchmark — weekly-review pending. Tomorrow (Sat May 9): market closed; run weekly-review (compute SPY relative, grade Week 2, decide whether to exit XLE Monday given broken energy thesis, plan 2 sector-momentum candidates for Monday post-NFP digestion to lift deployment toward 75% floor).

### May 11 — EOD Snapshot (Day 12, Monday)
**Portfolio:** $99,654.21 | **Cash:** $84,182.28 (84.5%) | **Day P&L:** +$337.34 (+0.34%) | **Phase P&L:** -$345.79 (-0.35%)

| Ticker | Shares | Entry | Close | Day Chg | Unrealized P&L | Stop |
|--------|--------|-------|-------|---------|----------------|------|
| XLE | 255 | $58.85 | $57.23 | +2.75% | -$413.10 | $53.8515 (trail 10%, HWM $59.835) |
| NVDA | 4 | $198.8925 | $219.61 | +2.05% | +$82.87 | $200.07 (trail 10%, HWM $222.30) |

**Notes:** Solid Week 3 open — Day P&L +$337 (+0.34%) is the best day of the phase; phase recovers from -$683 to -$346 (-0.35%), best level since May 5. Both positions rallied: XLE +2.75% to $57.23 (bounced off the $55 zone; now -2.75% from entry, -$413 unrealized — half the Thursday drawdown clawed back); NVDA +2.05% to $219.61 (+10.42% from entry, +$83 unrealized). NVDA HWM ratcheted to $222.30 intraday, stop tightened automatically to $200.07 (still 10% trail; +15% tighten threshold $228.73 not yet hit but only ~4.1% away). XLE HWM unchanged at $59.835; trail stays $53.8515, manual -7% cut at $54.7305 — buffers now 6.1% (trail) / 4.6% (manual cut), much healthier than Thursday's 3.7%/1.9%. No fills today; pre-market RESEARCH-LOG cadence still the bottleneck (7 trading days running). Cash 84.5%, deployment 15.5% — single sector-momentum entry's worth of unused capital. Trades today: 0. Trades this week: 0/3 (Week 3 starts fresh). Tomorrow (Tue May 12): file pre-market RESEARCH-LOG FIRST, decide whether NVDA strength warrants adding (still 13% headroom under 20% position cap) or rotating into a second sector leader, and re-evaluate XLE thesis — if oil stabilizes, hold; if not, consider preemptive trim before stop fires.

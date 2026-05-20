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

### May 13 — EOD Snapshot (Day 14, Wednesday)
**Portfolio:** $99,189.64 | **Cash:** $48,812.32 (49.2%) | **Day P&L:** -$556.59 (-0.56%) | **Phase P&L:** -$810.36 (-0.81%)

| Ticker | Shares | Entry | Close | Day Chg | Unrealized P&L | Stop |
|--------|--------|-------|-------|---------|----------------|------|
| MP | 281 | $65.14 | $63.87 | -2.62% | -$356.87 | $60.813 (trail 10%, HWM $67.57) |
| NVDA | 4 | $198.8925 | $226.04 | +2.38% | +$108.58 | $205.056 (trail 10%, HWM $227.84) |
| USAR | 663 | $25.74 | $25.40 | -0.59% | -$225.42 | $24.345 (trail 10%, HWM $27.05) |
| XLE | 255 | $58.85 | $57.59 | +0.04% | -$321.30 | $53.8515 (trail 10%, HWM $59.835) |

**Notes:** Red day — Day P&L -$557 (-0.56%) drags phase to a new low at -$810 (-0.81%); MP -2.62% to $63.87 was the main drag (-$357 unrealized, -1.95% from Tuesday's entry @ $65.14). Bookkeeping gap: TRADE-LOG missing EODs for May 11 (Mon) and May 12 (Tue), plus entry logs for MP (281 @ $65.14) and USAR (663 @ $25.74) — both filled Tue May 12 with GTC 10% trails attached (USAR order `49eebcec` stop $24.345 HWM $27.05; MP order `5b97e06a` stop $60.813 HWM $67.57). Deployment jumped from 15% to 50.8% on those two adds — biggest single-week deployment move of the phase, finally narrowing the gap to the 75–85% target band. NVDA the bright spot: +2.38% to $226.04 (+13.65% from entry, +$109 unrealized); HWM ratcheted to $227.84, stop auto-tightened to $205.056. +15% tighten threshold = $228.73 — current $226.04 is 1.2% below; one good day tomorrow flips the trail rule from 10% to 7% (new stop would be $211.89 if NVDA tags $228.73). XLE basically flat on the day to $57.59 (-2.14% from entry, -$321 unrealized, stop $53.8515 ~6.5% buffer); USAR -0.59% to $25.40 (-1.32% from entry, stop $24.345 ~4.2% buffer). No fills today. Trades today: 0. Trades this week: 2/3 entries used (MP + USAR Tue). One entry slot remains. Tomorrow (Thu May 14): file pre-market RESEARCH-LOG, monitor NVDA for +15% tighten trigger ($228.73), watch MP for day-2 follow-through weakness vs entry thesis, decide on final weekly entry slot if a clean sector-momentum signal appears — otherwise hold cash dry into Friday weekly-review.

## May 14 — Exit: USAR (trailing stop fired at open)
**Action:** SELL 663 USAR @ $24.27 | **Time:** 9:36 AM ET | **Order:** `49eebcec` (GTC trailing stop, auto-cancelled on fill)
**Entry:** $25.74 (May 12) | **Exit:** $24.27 | **Realized P&L:** -$974.61 (-5.71%)
**Reason:** 10% trailing stop GTC fired at $24.345 (HWM $27.05). Did NOT hit -7% manual cut threshold. Materials sector failed trade #1 of week.

## May 14 — Exit: MP (trailing stop fired at open)
**Action:** SELL 281 MP @ $60.80 | **Time:** 9:36 AM ET | **Order:** `5b97e06a` (GTC trailing stop, auto-cancelled on fill)
**Entry:** $65.14 (May 12) | **Exit:** $60.80 | **Realized P&L:** -$1,219.54 (-6.67%)
**Reason:** 10% trailing stop GTC fired at $60.813 (HWM $67.57). Did NOT hit -7% manual cut threshold ($60.58). Materials sector failed trade #2 of week → **Rule 10 SECTOR COOLDOWN: materials sector blocked until reset.**

## May 14 — Tighten: NVDA trail 10% → 7% (Rule 6, +15% threshold hit)
**Action:** Cancel order `576ea764` (10% trail, stop $212.823, HWM $236.47); place new GTC 7% trailing stop on 4 NVDA.
**New order:** `775288b4` — trail 7%, stop $218.95, HWM $235.43.
**Trigger:** NVDA +18.48% from entry ($198.8925 → $235.64) — above +15% threshold ($228.73), below +20% threshold ($238.67). Stop moved UP from $212.82 → $218.95 (never moved down). Current $235.64; new stop 7.1% below current = outside 3% buffer rule.

### May 14 — Midday Scan
**Positions snapshot:**

| Ticker | Shares | Entry | Last | P&L % | Unrealized P&L | Stop |
|--------|--------|-------|------|-------|----------------|------|
| NVDA | 4 | $198.8925 | $235.64 | +18.48% | +$146.99 | $218.95 (trail 7%, HWM $235.43) |
| XLE | 255 | $58.85 | $58.06 | -1.34% | -$201.45 | $53.8515 (trail 10%, HWM $59.835) |

**Actions taken:**
- Trail fires at open: USAR @ $24.27 (-5.71%, -$974.61) and MP @ $60.80 (-6.67%, -$1,219.54) — combined realized -$2,194.15.
- **Rule 10 triggered:** 2 consecutive failed materials trades (MP + USAR) → materials sector cooldown active. No new materials entries until reset.
- Tightened NVDA trail 10% → 7% on +15% threshold; new stop $218.95 (up from $212.82), HWM $235.43.
- XLE -1.34% from entry, no cut. Energy thesis remains broken-but-recovered; trail $53.85 with ~7.5% buffer to current $58.06.

**Cash/Equity:** Equity $97,737.62 (-$1,452 vs last_equity $99,172.88); cash $81,988.13 (83.9%); deployed 16.1% — collapsed back from 50.8% after MP+USAR exits.
**Trades this week:** 2/3 entries used (both stopped out same week — Rule 11 caution flag). 1 entry slot remains but materials blocked by sector cooldown.
**Plan:** Hold NVDA + XLE into close. No new entries today — 2 stop-outs same morning = stay defensive. Tomorrow (Fri May 15) is weekly-review day: compute SPY relative, assess whether sector approach is broken, decide entry plan for Week 4.

### May 15 — Midday Scan (no action)
**Positions snapshot:**

| Ticker | Shares | Entry | Last | P&L % | Unrealized P&L | Stop |
|--------|--------|-------|------|-------|----------------|------|
| NVDA | 4 | $198.8925 | $227.82 | +14.54% | +$115.71 | $219.9822 (trail 7%, HWM $236.54) |
| XLE | 255 | $58.85 | $59.105 | +0.43% | +$65.03 | $53.8515 (trail 10%, HWM $59.835) |

**Actions:** None.
**Step 3 (cut losers):** No position at or below -7%. NVDA +14.54%, XLE +0.43%.
**Step 4 (tighten winners):** NVDA already on 7% trail (tightened Thu when +15% threshold hit); +20% threshold = $238.67 (HWM $236.54, current $227.82 — not yet hit). Stop $219.98 vs current $227.82 = 3.4% buffer, outside the 3% rule. No further tighten. XLE +0.43% — below any tighten threshold.
**Step 5 (thesis check):** NVDA earnings Tue May 20 AMC; pre-market plan = HOLD through, let trail protect ($219.98 locks ~$84 of $116 unrealized). XLE thesis recovered as WTI bounced $93 → ~$105; breakout setup intact. Both holds confirmed.
**Cash/Equity:** Equity ~$97,971 (mark-to-market); cash $81,988.13 (83.7%); deployment ~16.3%. No fills today.
**Trades this week:** 2/3 (MP + USAR — both stopped out same week). 1 slot remains but materials blocked by Rule 10 cooldown; no clean signal to deploy on Friday into NVDA-earnings week.

### May 14 — EOD Snapshot (Day 15, Thursday)
**Portfolio:** $97,735.80 | **Cash:** $81,988.13 (83.9%) | **Day P&L:** -$1,453.84 (-1.47%) | **Phase P&L:** -$2,264.20 (-2.26%)

| Ticker | Shares | Entry | Close | Day Chg | Unrealized P&L | Stop |
|--------|--------|-------|-------|---------|----------------|------|
| NVDA | 4 | $198.8925 | $235.91 | +4.46% | +$148.07 | $219.9822 (trail 7%, HWM $236.54) |
| XLE | 255 | $58.85 | $58.055 | +0.74% | -$202.73 | $53.8515 (trail 10%, HWM $59.835) |

**Notes:** Worst day of the phase — Day P&L -$1,454 (-1.47%) drags phase to a new low at -$2,264 (-2.26%). Two trailing stops fired at the open (9:36 ET): USAR @ $24.27 (-5.71%, realized -$974.61) and MP @ $60.80 (-6.67%, realized -$1,219.54) — combined realized -$2,194.15 on the day. Both materials trades stopped out same week they were opened (Rule 11 caution flag). **Rule 10 triggered: 2 consecutive failed materials trades → materials sector cooldown active.** Survivors carried the rest of the day: NVDA +4.46% to $235.91 (+18.61% from entry, +$148 unrealized) — crossed the +15% threshold ($228.73), so trail tightened 10% → 7% via order replacement (cancel `576ea764`, new GTC `775288b4`, stop $219.98, HWM $236.54). XLE +0.74% to $58.055 (-1.35% from entry, -$203 unrealized); stop unchanged at $53.8515, HWM $59.835. Cash $81,988 (83.9%); deployment collapsed from 50.8% Wed → 16.1% today after the two stop-outs. Trades today: 2 (both exits — USAR SELL, MP SELL; plus NVDA trail-tighten order replacement). Trades this week: 2/3 entries used (MP + USAR, both round-tripped — net negative). One entry slot remains but materials blocked by sector cooldown. Tomorrow (Fri May 15): weekly-review day — compute SPY relative for Week 3, grade phase performance (now -2.26% vs +0.13% peak May 5), assess whether the sector-momentum approach is broken (2-for-2 stop-outs in materials, XLE energy thesis already broken), decide whether to exit XLE preemptively, and plan Week 4 entry strategy if any. No new entries Friday absent a clean signal — defensive bias holds.

## May 18 — Exit: NVDA (trailing stop fired pre-earnings)
**Action:** SELL 4 NVDA @ $219.9275 | **Time:** 12:30 PM ET | **Order:** `775288b4` (GTC 7% trailing stop, auto-cancelled on fill)
**Entry:** $198.8925 (May 5) | **Exit:** $219.9275 | **Realized P&L:** +$84.14 (+10.58%)
**Reason:** 7% trailing stop GTC fired at $219.9822 (HWM $236.54). Did NOT hit -7% manual cut. Pre-earnings de-risking 2 days before Wed AMC earnings — trail locked the gain. NVDA bounced post-stop to ~$222.40, but discipline holds: flat into Wed binary (earnings + FOMC minutes) is correct R:R.

### May 18 — Midday Scan
**Positions snapshot:**

| Ticker | Shares | Entry | Last | P&L % | Unrealized P&L | Stop |
|--------|--------|-------|------|-------|----------------|------|
| XLE | 255 | $58.85 | $60.395 | +2.625% | +$393.98 | $54.603 (trail 10%, HWM $60.67) |

**Actions taken:**
- NVDA trail fired at 12:30 PM ET @ $219.9275 → realized +$84.14 (+10.58%). First green realized exit of the phase. Flat into Wed AMC earnings + FOMC minutes — correct R:R.
- XLE: no action. HWM auto-ratcheted from $59.835 → $60.67 (today's high); stop auto-tightened from $53.8515 → $54.603 (still 10% trail).

**Step 3 (cut losers):** No positions at or below -7%. XLE +2.625%.
**Step 4 (tighten winners):** XLE +2.625%, below +15% threshold ($67.68). No manual tighten.
**Step 5 (thesis check):** XLE thesis intact (energy #1 sector YTD, WTI $101, Brent $110, Iran/Hormuz premium). NVDA already exited via trail — clean.
**Cash/Equity:** Equity $98,268.41 (+$221.96 vs last_equity $98,046.45); cash $82,867.68 (84.3%); deployment ~15.7%.
**Trades this week:** 0/3 entries used (NVDA exit doesn't count). Materials cooldown still active. Defer fresh entries until post-Wed event clarity (NVDA AMC + FOMC minutes).

### May 15 — EOD Snapshot (Day 16, Friday)
**Portfolio:** $98,034.53 | **Cash:** $81,987.97 (83.6%) | **Day P&L:** +$295.75 (+0.30%) | **Phase P&L:** -$1,965.47 (-1.97%)

| Ticker | Shares | Entry | Close | Day Chg | Unrealized P&L | Stop |
|--------|--------|-------|-------|---------|----------------|------|
| NVDA | 4 | $198.8925 | $224.9457 | -4.58% | +$104.21 | $219.9822 (trail 7%, HWM $236.54) |
| XLE | 255 | $58.85 | $59.45 | +2.38% | +$153.00 | $53.8515 (trail 10%, HWM $59.835) |

**Notes:** Modest green close to a red week. Day P&L +$296 (+0.30%) trims phase from Thursday's low (-2.26%) to -1.97% ($98,034.53 vs $100,000 baseline). XLE staged the rebound: +2.38% to $59.45 (+1.02% from entry, +$153 unrealized) on WTI bounce ($93 → ~$105) — first green from entry since week 1; stop unchanged at $53.8515 (HWM $59.835 — current $59.45 is $0.385 below HWM, no auto-ratchet today). NVDA pulled back -4.58% to $224.9457 (+13.10% from entry, +$104 unrealized) ahead of next-Tue (May 20) AMC earnings; HWM $236.54 held, 7% trail stop $219.98 = 2.21% buffer to current — INSIDE the 3% rule, but stop never moves down so it stays. +20% threshold ($238.67) not hit; no further tighten. Cash $81,988 (83.6%), deployment ~16.4% — unchanged from Thu post-stopouts; materials sector remains blocked by Rule 10 cooldown. No fills today; no new entries (no clean signal + defensive bias post 2-for-2 materials stop-outs). Trades today: 0. Trades this week: 2/3 (MP + USAR — both stopped out same week, Rule 11 caution flag). Week 3 closes red vs prior phase peak; weekly-review pending. Tomorrow (Sat May 16): market closed — run weekly-review (compute SPY relative for Week 3, grade phase, formally assess whether sector-momentum approach is broken, decide Week 4 entry plan, NVDA-earnings (Tue AMC) hold-through plan, and whether to take XLE off the table preemptively now that it's green from entry).

### May 19 — Midday Scan (no action)
**Positions snapshot:**

| Ticker | Shares | Entry | Last | P&L % | Unrealized P&L | Stop |
|--------|--------|-------|------|-------|----------------|------|
| XLE | 255 | $58.85 | $61.09 | +3.81% | +$571.20 | $55.053 (trail 10%, HWM $61.17) |

**Actions:** None.
**Step 3 (cut losers):** XLE +3.81%, not at -7%. No cut.
**Step 4 (tighten winners):** XLE +3.81%, below +15% threshold ($67.68). HWM auto-ratcheted $60.70 → $61.17; trail auto-tightened $54.63 → $55.053 (still 10%). No manual tighten.
**Step 5 (thesis check):** XLE thesis intact — energy #1 YTD, WTI $103, Brent $110, Iran/Hormuz premium. Hold.
**Phantom MP order (`be0e8777`):** NOT in current orders list — already cancelled / never filled. Confirmed flat MP. Pre-market priority resolved cleanly.
**Cash/Equity:** Cash $82,867.67 (84.2%); equity ~$98,446 (mark-to-market); deployment ~15.8%. No fills today.
**Trades this week:** 0/3 entries used. Materials cooldown active. Defer fresh entries until post-Wed binary (NVDA AMC + FOMC minutes).

### May 18 — EOD Snapshot (Day 17, Monday)
**Portfolio:** $98,328.33 | **Cash:** $82,867.68 (84.3%) | **Day P&L:** +$281.88 (+0.29%) | **Phase P&L:** -$1,671.67 (-1.67%)

| Ticker | Shares | Entry | Close | Day Chg | Unrealized P&L | Stop |
|--------|--------|-------|-------|---------|----------------|------|
| XLE | 255 | $58.85 | $60.63 | +2.00% | +$453.90 | $54.63 (trail 10%, HWM $60.70) |

**Notes:** Green open to Week 4. Day P&L +$282 (+0.29%) lifts phase from Friday's -1.97% to -1.67% ($98,328.33 vs $100,000 baseline) — best phase mark since May 12. Single realized exit today: NVDA 7% trail fired at 12:30 PM ET @ $219.9275 (HWM $236.54), locking +$84.14 (+10.58%) on the May 5 entry — first green realized exit of the phase and correct pre-earnings de-risk (NVDA AMC Wed May 20 + FOMC minutes same day = binary risk we don't want to hold through with one position carrying 30% of remaining deployment). NVDA bounced post-stop to ~$222.40, but discipline holds — trail rules locked the gain before the binary. XLE the survivor and the standout: +2.00% on the day to $60.63 (+3.02% from entry, +$454 unrealized — biggest unrealized P&L of the phase on this name), riding the energy bid (WTI $101, Brent $110, Iran/Hormuz premium intact). HWM auto-ratcheted $59.835 → $60.70 today; stop auto-tightened $53.8515 → $54.63 (still 10% trail; +15% tighten threshold = $67.68, not close). XLE alone now carries the book. Cash $82,868 (84.3%), deployment 15.7% — well below the 75-85% target band; only one position open. Trades today: 1 (NVDA SELL trail fill). Trades this week: 0/3 entries used (NVDA exit doesn't count as new entry). Materials cooldown still active (Rule 10). Tomorrow (Tue May 19): pre-market RESEARCH-LOG, monitor XLE for continued energy momentum, scan for clean non-materials sector signals to deploy the entry slot — but stay defensive into Wed AMC NVDA earnings + FOMC minutes (don't open new positions Tue that would carry through Wed's binary unless setup is exceptional). Weekly-review still pending from Fri close.

### May 19 — EOD Snapshot (Day 18, Tuesday)
**Portfolio:** $98,454.06 | **Cash:** $82,837.86 (84.1%) | **Day P&L:** +$125.73 (+0.13%) | **Phase P&L:** -$1,545.94 (-1.55%)

| Ticker | Shares | Entry | Close | Day Chg | Unrealized P&L | Stop |
|--------|--------|-------|-------|---------|----------------|------|
| XLE | 255 | $58.85 | $61.24 | +1.09% | +$609.45 | $55.341 (trail 10%, HWM $61.49) |

**Notes:** Quiet green Tuesday. Day P&L +$126 (+0.13%) extends Monday's recovery, lifting phase from -1.67% to -1.55% ($98,454.06 vs $100,000 baseline) — new post-May-12 high-water mark. No fills, no new entries, no stop changes by hand. XLE the lone position kept doing its job: +1.09% to $61.24 (+4.06% from entry, +$609 unrealized — biggest unrealized P&L of the phase) on continued energy bid (WTI $103, Brent $110, Iran/Hormuz premium intact, energy still #1 YTD sector). HWM auto-ratcheted $60.70 → $61.49 today; trail auto-tightened $54.63 → $55.341 (still 10%; +15% tighten threshold = $67.68, not close). Phantom MP order resolved at midday — confirmed cancelled / not in active orders. Cash $82,838 (84.1%), deployment 15.9% — still well below 75-85% target; XLE alone carries the book. Trades today: none. Trades this week: 0/3 entries used. Materials cooldown still active (Rule 10). Tomorrow (Wed May 20) is the binary day: NVDA AMC earnings + FOMC minutes — defensive bias holds, no new entries that would compound risk into the close; let XLE ride with trail protection ($55.341 locks ~$425 of $609 unrealized). Post-Wed (Thu May 21), if NVDA prints clean and FOMC minutes don't shock, scan for the Week-4 entry slot — non-materials, sector-momentum signal required.

### May 20 — Midday Scan (no action)
**Positions snapshot:**

| Ticker | Shares | Entry | Last | P&L % | Unrealized P&L | Stop |
|--------|--------|-------|------|-------|----------------|------|
| XLE | 255 | $58.85 | $60.155 | +2.22% | +$332.78 | $55.53 (trail 10%, HWM $61.70) |

**Actions:** None.
**Step 3 (cut losers):** XLE +2.22%, not at -7%. No cut.
**Step 4 (tighten winners):** XLE +2.22%, below +15% threshold ($67.68). HWM auto-ratcheted $61.49 → $61.70; trail auto-tightened $55.341 → $55.53 (still 10%). No manual tighten.
**Step 5 (thesis check):** XLE thesis intact — energy #1 YTD (+20-22%), WTI ~$102, Brent ~$110, Iran/Hormuz premium intact. Hold.
**Binary day:** NVDA AMC earnings + FOMC minutes 2 PM ET. Already flat NVDA (exited May 18 trail). No direct gap risk. No new entries today per pre-market plan.
**Cash/Equity:** Cash $82,837.79 (84.2%); equity ~$98,177 (mark-to-market, XLE -1.85% intraday from $61.29 lastday); deployment ~15.6%. No fills today.
**Trades this week:** 0/3 entries used. Materials cooldown active. Thu/Fri remain the deployment window post-NVDA + FOMC clarity.

### May 20 — EOD Snapshot (Day 19, Wednesday)
**Portfolio:** $98,109.74 | **Cash:** $82,837.79 (84.4%) | **Day P&L:** -$357.00 (-0.36%) | **Phase P&L:** -$1,890.26 (-1.89%)

| Ticker | Shares | Entry | Close | Day Chg | Unrealized P&L | Stop |
|--------|--------|-------|-------|---------|----------------|------|
| XLE | 255 | $58.85 | $59.89 | -2.28% | +$265.20 | $55.53 (trail 10%, HWM $61.70) |

**Notes:** Red binary day. Day P&L -$357 (-0.36%) gives back the Mon-Tue recovery and prints a new post-May-12 phase low at -1.89% ($98,109.74 vs $100,000 baseline). XLE the lone position took the hit: -2.28% intraday from $61.29 → $59.89 (still +1.77% from $58.85 entry, +$265 unrealized) as energy gave back some of the recent bid into the FOMC minutes (2 PM ET) and pre-NVDA-AMC de-risking. HWM unchanged at $61.70 (intraday high $61.70 came earlier); trail stop $55.53 (10%) — locks ~$170 of $265 unrealized; buffer to current = $4.36 = 7.3%, well outside the 3% rule. No fills today, no manual stop changes, no new entries. Cash $82,838 (84.4%), deployment 15.6% — still well below 75-85% target band; XLE alone carries the book. Trades today: 0. Trades this week: 0/3 entries used. Materials sector cooldown still active (Rule 10). Binary calendar resolved: NVDA AMC prints tonight (we are flat — exited May 18 trail at $219.93, +10.58% realized) and FOMC minutes already crossed at 2 PM ET. Tomorrow (Thu May 21): pre-market RESEARCH-LOG with NVDA print reaction + post-FOMC minutes read; if energy thesis holds and a non-materials sector signal is clean, deploy the Week-4 entry slot (1 of 3 used, 2 remaining for Thu/Fri window) — defensive bias eases now that the binary is past, but sizing stays disciplined (max 20% / pos).

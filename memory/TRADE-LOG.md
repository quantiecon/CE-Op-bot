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

# Trading Strategy

## Mission
Beat the S&P 500 (benchmark: SPY) over the challenge window. Stocks only — no options, ever.

## Capital & Constraints
- Starting capital: ~$100,000 (Alpaca paper)
- Platform: Alpaca (paper by default)
- Instruments: Stocks ONLY
- PDT limit: N/A at this equity level (account is > $25k, so no 3-day-trade / 5-rolling-day cap)
## FTC abolishd PDT?
- 20% per-position cap = ~$20,000 max cost per trade

## Core Rules
1. NO OPTIONS — ever
2. 75-85% deployed
3. 5-6 positions at a time, max 20% each
4. 10% trailing stop on every position as a real GTC order
5. Cut losers at -7% manually
5a. **Thesis-invalidated discretionary exit**: if the position's entry thesis is explicitly invalidated (e.g., underlying macro catalyst broken) AND the trail buffer is ≤ 3% of current price, exit at the next session open — do not wait for the GTC trail or the -7% manual cut to fire. (Added Wk 5 review 2026-05-29 after carrying XLE on a dead sub-$90-oil thesis into review with ~1.4% trail buffer.)
6. Tighten trail: 7% at +15%, 5% at +20%
6a. **HWM-resistance partial-trim**: at +5-7% unrealized within 1% of the position's HWM, into a Fri close or a mid-week macro binary, a 20-33% partial trim is permissible to lock partial gain and free capital for probe redeploy. Optional risk management (not mandatory); trailing GTC quantity must be reduced to match remaining position. (Added Wk 11 review 2026-07-10 after 3 consecutive weekly datapoints: Wk 9 XLI Thu→Fri $260 give-back, Wk 10 XLI Tue→Thu $103 give-back, Wk 11 XLI Mon→Fri $313 give-back — all at HWM resistance approaches; Rule 6 tighten thresholds at +15%/+20% do not fire at these +5-7% ceilings.)
7. Never within 3% of current price; never move a stop down
8. Max 3 new trades per week
9. Follow sector momentum
10. Exit a sector after 2 consecutive failed trades
11. Patience > activity

## Entry Checklist
- Specific catalyst?
- Sector in momentum?
- Stop level (7-10% below entry)
- Target (min 2:1 R:R)

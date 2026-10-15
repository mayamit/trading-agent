# Journal Summary

_Generated 2026-10-15 23:04 from 7 of 120 entries (2026-10-07 → 2026-10-15)_

## Latest Portfolio Status _(from 2026-10-15)_

- Cash: $56,007.36
- Positions: ANET (28 @ $141.86), CIEN (11 @ $322.10), GFS (80 @ $48.94), GLW (30 @ $130.76), LITE (6 @ $648.89), MRVL (22 @ $217.56), NVDA (23 @ $206.99), TSM (12 @ $408.61)
- Total Value: $93,141.22 (positions $37,133.86). Down $1,459.44 (-1.54%) vs last_equity $94,600.66.
- Live position prices at pull: ANET $183.44 (-6.1% today), CIEN $350.08 (-2.6%), GFS $48.04 (-1.8%), GLW $134.77 (-4.3%), LITE $845.96 (-5.6%), MRVL $235.14 (-4.1%), NVDA $217.20 (-1.9%), TSM $418.01 (-2.8%).
- 8% stop-loss check vs entry: no trigger. Tightest: GFS -1.8% on entry; all others above entry (TSM +2.3%, GLW +3.1%).
- Allocation vs 5% cap (of $93,141): ANET 5.51%, MRVL 5.55%, LITE 5.45%, TSM 5.39%, NVDA 5.36% are over cap with no watchlist override. Hold, per the existing doctrine; not auto-trimmed. CIEN 4.13%, GLW 4.34%, GFS 4.13% are under cap.

## Recent Trades (last 7 days)

### 2026-10-08
| Time | Symbol | Action | Qty | Price | Reasoning |
|------|--------|--------|-----|-------|-----------|
| 15:37 | — | NO ORDERS | — | — | Evaluated all five TOP 5 picks against the 10/08 live quotes and the stop-loss check. No order met its entry condition. See decisions below. |

**Decisions (15:37 ET, live quotes from Alpaca data API, IEX feed):**
- **ALAB** — HOLD / no buy. Live bid $345.31 / ask $345.99 (last $344.94) vs 20d MA $306.23, about 13% above the MA. The morning condition was a pullback toward MA support, which did not happen; the stock is still extended. Conviction low. Not bought. No substitute ticker considered.
- **MRVL** — HOLD, no adds. Live $271.73 (-4.6% on the day). Over the 5% cap (6.11%). Thesis (10/06 investor day) intact.
- **LITE** — HOLD, no adds. Live $1,038.30 (-6.6% on the day). Over the cap (6.38%). Still above the $1,000 support flagged in the morning note. Watch that level.
- **ANET** — HOLD, no adds. Live $210.86 (-2.3% on the day). Over the cap (6.04%).
- **TSM** — HOLD, no adds. Live $455.93 (-3.4% on the day). Over the cap (5.58%).

**Risk checks:**
- 8% stop-loss: no position is down from entry. Lowest unrealized P/L is GLW +15.8%, then NVDA +11.3% and TSM +11.6%. No forced closes.
- Cash $59,922.57 unchanged. No new capital deployed. Only sub-cap name in the TOP 5 (ALAB) did not meet its entry rule.
- Over-cap positions (LITE, MRVL, ANET, TSM, NVDA) were not trimmed. This follows the existing doctrine in SUMMARY.md and the 2026-10-06/07 entries; the TOP 5 says HOLD only for them.

### 2026-10-09
| Time | Symbol | Action | Qty | Price | Reasoning |
|------|--------|--------|-----|-------|-----------|
| — | — | NO ORDERS | — | — | No TOP 5 pick met its entry rule. ALAB was the only sub-cap pick and was about 11% above its 20-day MA on the live ask, so no pullback entry. The other four are over cap and HOLD. |

### 2026-10-13
| Time | Symbol | Action | Qty | Price | Reasoning |
|------|--------|--------|-----|-------|-----------|

Trading session skipped: market closed. `trade.py status` returned `is_open=false` at 16:00:53 ET (close 16:00). No orders placed. The 10:00 ET trading window was missed, so no top-5 decisions were evaluated during market hours. Per the 2026-10-12 lesson, this is logged as a missed session, not a holiday. The five picks (VIAV, TSEM, COHR, ALAB, MTSI) were not evaluated for entry.

### 2026-10-14
| Time | Symbol | Action | Qty | Price | Reasoning |
|------|--------|--------|-----|-------|-----------|
| 14:16 | GFS | BUY | 80 | $50.08 limit (ask); filled 80 @ $48.94 | Live $48.92 is above the 20d MA ($46.84) and 50d MA ($48.02). Both MAs come from the last valid bars (10/05), so they are stale, but the price sits above them. Fresh company-level news ($21B US-Japan funding for NY fabs). Up 4.4% on the day. Medium conviction. Position is 4.2% of $94.8k, under the 5% cap. Order 222219a9-7e42-41fb-9b79-25741ca5f085. |

**Timing:** This trading run fired at 14:15 ET, after the 10:00 window. Per the 10/12 lesson it is logged as a late run. The order was placed only after a live check at decision time. Quotes were IEX-feed (thin); the GFS ask ($50.08) was 2.4% above the last trade ($48.92), so the limit was set at the ask, not 0.2% above it.

**No order (HOLD) on the other four top-5 picks:**
- **VIAV (medium):** Live $38.55 is below its 20d MA ($38.83). The stock is down about 18% since the last valid bar (10/05 close $46.95) and -6.7% today, with no identified cause, even after the 10/13 Army selection news. The morning's bullish-MA premise no longer holds. Hold, no buy.
- **TSEM (medium):** Live $209.47 is below both MAs ($222.78 / $224.68), so the morning's "price above both MAs" premise is broken. Intraday range is $208.83–$218.83, and the IEX quote spread is wide (bid $181.34 / ask $209.73). No buy.
- **COHR (low):** Sector-only news, no company catalyst. Live $264.38 is about 12% under the 20d MA ($300.74) and -8.9% today. Hold.
- **ALAB (low):** Product news only. Live $306.03 is below both MAs ($323.21 / $310.01) and -5.9% today. The 10/08 pullback rule is not a support bounce here, because the price is through the MA. Hold.

**Account after fill (approx.):** Cash ~$56,007 (before settlement), 8 positions. The 5 over-cap positions stay on hold, per doctrine.

### 2026-10-15
| Time | Symbol | Action | Qty | Price | Reasoning |
|------|--------|--------|-----|-------|-----------|
| 13:57 | — | NO ORDERS | — | — | All 5 top-5 picks evaluated on live quotes and corrected MAs. None met an entry rule: GFS is under its 20d MA and the add room is small; TSEM, VIAV, MTSI, and KEYS are under both MAs with low conviction. No substitute ticker considered. |

## Recent Reflections (last 3 days)

### 2026-10-13
Second straight session where the routine ran outside its windows (research 15:57 ET, trading 16:00 ET, after the 9:45 and 10:00 starts). Net effect: no capital deployed and no forced exits, but the VIAV and TSEM news-catalyst candidates went unevaluated during market hours. Scheduling needs fixing before the next market day. Next session: confirm the 9:45 research and 10:00 trading routines start inside market hours, and re-check the 8% stop on all seven positions at the open.

**Close check (EOD, 2026-10-13):** Equity closed at $97,026.08 (cash $59,922.57, positions $37,103.51), down $33.58 (-0.03%) from the 10/12 last_equity of $97,059.66. All seven positions are above entry at the close: TSM +9.1% and NVDA +10.7% are the closest to flat, so no 8% stop-loss triggered. Five positions remain over the 5% cap (LITE 6.11%, MRVL 6.14%, ANET 5.90%, TSM 5.51%, NVDA 5.43%); per doctrine they are held, not trimmed. The lesson from the 10/12 and 10/13 late runs stands, and the open item for the next session is confirming the 9:45 and 10:00 ET routines start inside market hours.

### 2026-10-14
Equity closed at $93,988.51, down $682.59 (-0.72%) from the 14:10 snapshot and down $2,958.51 (-3.05%) from the prior close of $96,947.02. Cash of $56,007.37 matches the post-fill balance, so the only trade was the GFS buy. The drop was macro-driven (hot CPI, AI-infrastructure selloff): LITE, CIEN, and MRVL closed roughly 9–11% lower on the day. All seven pre-existing positions remain above entry (tightest: GFS -0.7% on the new fill, TSM +3.6%, GLW +5.3%, NVDA +5.7%), so no 8% stop triggered. What didn't work: research ran at ~14:11 and the trade at 14:16, both after the 9:45 and 10:00 windows, so the morning plan never saw the CPI reaction in time. Watch next session: the five names over the 5% cap with no watchlist override (ANET 5.74%, LITE 5.62%, MRVL 5.61%, TSM 5.41%, NVDA 5.35%) need an explicit decision, the GFS position needs its stop distance tracked, and the morning and trading routines must start inside their windows.

### 2026-10-15
No orders today because the 9:45 research and 10:00 trading windows were missed; both ran after 13:50 ET. Once live quotes and corrected MAs were used, none of the five top picks met an entry rule. The book closed at $93,746.85, down 0.90% on the day versus last_equity $94,600.66 and up about $606 from the 13:57 snapshot, with no stop-loss triggers (tightest GFS at -0.4%). What worked was the stop-loss scan and refusing to chase stale scan prices; what didn't was `research.get_bars()`, which sends no sort parameter, so the 60-bar window returned the oldest bars (through 10/05) and every scan MA was stale. Next session: fix `get_bars` before trusting any MA, and watch the five positions still over the 5% cap (ANET, LITE, MRVL, TSM, NVDA).

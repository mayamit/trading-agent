# Journal Summary

_Generated 2026-10-16 22:51 from 7 of 121 entries (2026-10-08 → 2026-10-16)_

## Latest Portfolio Status _(from 2026-10-16)_

- Cash: $56,007.36
- Positions: ANET (28 @ $141.86), CIEN (11 @ $322.10), GFS (80 @ $48.94), GLW (30 @ $130.76), LITE (6 @ $648.89), MRVL (22 @ $217.56), NVDA (23 @ $206.99), TSM (12 @ $408.61)
- Total Value: $92,652.60 (positions $36,645.24), down $1,114.23 (-1.19%) vs last_equity $93,766.83 (intraday, 13:41 ET)
- 8% stop-loss check (entry basis): no trigger. Tightest: GFS -3.4% ($47.27 vs $48.94). All others above entry.
- 5% cap check (live, of $92,652.60): LITE 5.46%, MRVL 5.51%, TSM 5.37%, NVDA 5.36%, ANET 5.40% are over cap with no watchlist override. Held per doctrine, not trimmed, and not added to. CIEN 4.02%, GLW 4.34%, GFS 4.08% are under cap.

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

### 2026-10-16
| Time | Symbol | Action | Qty | Price | Reasoning |
|------|--------|--------|-----|-------|-----------|
| 13:47 | — | NO ORDERS | — | — | No top-5 pick met its entry rule on live quotes. Late run: the 10:00 ET window was missed, and the decision was made on the 13:47 ET quotes. |

**Decisions (13:47 ET, Alpaca IEX latest quotes and snapshots):**
- **CSCO** — HOLD / no buy. Mid $107.62 (bid $107.59 / ask $107.64). Still under the 20d MA ($111.17). No reclaim, so no entry.
- **AVGO** — HOLD / no buy. Mid $332.94 (bid $332.84 / ask $333.03). About 6.4% under the 20d MA ($355.65). No reclaim.
- **GFS** — HOLD, no add. Ask $47.29, last $47.245, -3.5% from the $48.94 entry. Still under the 20d MA ($48.21). Add room exists, but the entry rule (live reclaim of the 20d MA) is not met.
- **VIAV** — NO BUY. Mid $34.26 (bid $34.23 / ask $34.29). The trend is still broken, about 17% under the 20d MA ($41.36). The contract news alone does not justify a buy.
- **KEYS** — NO BUY. Bid $335.23 / ask $337.55 (wide, IEX). Last $337.18, under both MAs. No fresh catalyst.

**Risk checks:**
- 8% stop-loss: no trigger. Tightest is GFS at -3.5% from entry. The other positions are above entry (ANET +25.8%, LITE +29.7%, MRVL +6.5%, NVDA +4.2%, GLW +2.5%, TSM +1.3%, CIEN +5.0%). No forced closes.
- Cash $56,007.36 unchanged. No new capital deployed.
- Over-cap positions (LITE, MRVL, NVDA, TSM, ANET) stay held per doctrine. None were trimmed or added to.

## Recent Reflections (last 3 days)

### 2026-10-14
Equity closed at $93,988.51, down $682.59 (-0.72%) from the 14:10 snapshot and down $2,958.51 (-3.05%) from the prior close of $96,947.02. Cash of $56,007.37 matches the post-fill balance, so the only trade was the GFS buy. The drop was macro-driven (hot CPI, AI-infrastructure selloff): LITE, CIEN, and MRVL closed roughly 9–11% lower on the day. All seven pre-existing positions remain above entry (tightest: GFS -0.7% on the new fill, TSM +3.6%, GLW +5.3%, NVDA +5.7%), so no 8% stop triggered. What didn't work: research ran at ~14:11 and the trade at 14:16, both after the 9:45 and 10:00 windows, so the morning plan never saw the CPI reaction in time. Watch next session: the five names over the 5% cap with no watchlist override (ANET 5.74%, LITE 5.62%, MRVL 5.61%, TSM 5.41%, NVDA 5.35%) need an explicit decision, the GFS position needs its stop distance tracked, and the morning and trading routines must start inside their windows.

### 2026-10-15
No orders today because the 9:45 research and 10:00 trading windows were missed; both ran after 13:50 ET. Once live quotes and corrected MAs were used, none of the five top picks met an entry rule. The book closed at $93,746.85, down 0.90% on the day versus last_equity $94,600.66 and up about $606 from the 13:57 snapshot, with no stop-loss triggers (tightest GFS at -0.4%). What worked was the stop-loss scan and refusing to chase stale scan prices; what didn't was `research.get_bars()`, which sends no sort parameter, so the 60-bar window returned the oldest bars (through 10/05) and every scan MA was stale. Next session: fix `get_bars` before trusting any MA, and watch the five positions still over the 5% cap (ANET, LITE, MRVL, TSM, NVDA).

### 2026-10-16
No orders today. Every top-5 pick is low conviction and below its 20d MA, and none reclaimed its MA on live quotes. The routine ran late, at 13:42 research and 13:47 trading, so the 9:45 and 10:00 windows were missed again. The 10/12 lesson applies: this session is logged as a late run. Once live quotes are used, the decision was still HOLD on every name. Equity was $92,602 at 13:46 ET, down about 1.2% on the day, with no stop triggers. Tomorrow: confirm the 9:45 and 10:00 ET routines start inside their windows, and fix `get_bars` sorting before the scan MAs are trusted again.

**Close update (EOD fetch, 10/16):** Equity closed at $92,054.77 vs last_equity $93,766.83, down $1,712.06 (-1.83%). That is $598 below the 13:41 intraday mark ($92,652.60). Cash is unchanged at $56,007.36 and no orders were placed. Positions are still 8 names, with market value $36,047.41. Closing marks: GFS $46.43 (-5.1% from $48.94 entry, the tightest name, still above the 8% stop). LITE, MRVL, NVDA, TSM, and ANET remain over the 5% cap with no watchlist override, so they stay held. No new lesson: the no-trade outcome matches the existing 10/12 and 10/15 lessons. Tomorrow: check GFS against the 8% line (about $45.02) at the open.

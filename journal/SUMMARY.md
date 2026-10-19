# Journal Summary

_Generated 2026-10-19 23:40 from 7 of 122 entries (2026-10-09 → 2026-10-19)_

## Latest Portfolio Status _(from 2026-10-19)_

- Cash: $56,007.36
- Positions: ANET (28 @ $141.86, now $183.75), CIEN (11 @ $322.10, now $346.49), GFS (80 @ $48.94, now $46.58), GLW (30 @ $130.76, now $133.19), LITE (6 @ $648.89, now $841.41), MRVL (22 @ $217.56, now $238.94), NVDA (23 @ $206.99, now $217.98), TSM (12 @ $408.61, now $423.23)
- Total Value: $93,084.79 (positions $37,077.43), up $934.21 (+1.01%) vs last_equity $92,150.58 (intraday)
- 8% stop-loss check (entry basis): no trigger. Tightest: GFS -4.8% ($46.58 vs $48.94; stop line $45.02). All others above entry.
- 5% cap check (live, of $93,084.79): ANET 5.53%, LITE 5.42%, MRVL 5.65%, TSM 5.46%, NVDA 5.39% are over cap with no watchlist override. Held per doctrine, not trimmed, not added to. CIEN 4.09%, GLW 4.29%, GFS 4.00% are under cap.

## Recent Trades (last 7 days)

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

### 2026-10-19
_Trading routine ran 15:36 ET (late run; the 10:00 window was missed). Market open, closes 16:00._

| Time | Symbol | Action | Qty | Price | Reasoning |
|------|--------|--------|-----|-------|-----------|
| 15:36 | — | NO ORDERS | — | — | All 5 top-5 picks evaluated on live quotes (IEX) and recomputed MAs. None met an entry rule. No substitute ticker considered. |

**Decisions (15:36 ET, live quotes and recomputed MAs):**
- **AVGO** — HOLD / no buy. Bid $336.08 / ask $340.00 (wide), last close $336.13. Still below the 20d ($354.09) and 50d ($363.89). No live reclaim of the 20d MA.
- **CSCO** — HOLD / no buy. Bid $106.68 / ask $106.78, last $106.81. Below the 20d ($110.91) and 50d ($111.33). The capex headline is not enough without an MA reclaim.
- **CRDO** — HOLD / no buy. Bid $175.16 / ask $181.31 (wide, IEX), last $175.31. Below the 20d ($199.26) and 50d ($204.52). Premarket bounce only, not a trend entry.
- **GLW** — HOLD, no add. Bid $133.26 / ask $133.35, last $133.28. Below the 20d ($152.75) and 50d ($153.78). The morning's add condition (MA reclaim) is not met. Position is under cap (about 4.3%), so the add room exists but is not used.
- **VIAV** — NO BUY. Bid $34.81 / ask $34.94, last $34.945. Below the 20d ($41.25) and 50d ($39.18). The 10/13 contract is discounted and does not justify entry against a broken trend.

**Risk checks:**
- 8% stop-loss: no trigger. Tightest is GFS at -4.4% from the $48.94 entry (ask ~$46.79; stop line $45.02). No forced closes.
- Cash $56,007.36 unchanged. No new capital deployed.
- Over-cap positions (ANET, LITE, MRVL, TSM, NVDA) held per doctrine. Not trimmed, not added to.
- No SELL signal on any held name. Held names are not in today's top 5, and no thesis is broken on the morning data.

## Recent Reflections (last 3 days)

### 2026-10-15
No orders today because the 9:45 research and 10:00 trading windows were missed; both ran after 13:50 ET. Once live quotes and corrected MAs were used, none of the five top picks met an entry rule. The book closed at $93,746.85, down 0.90% on the day versus last_equity $94,600.66 and up about $606 from the 13:57 snapshot, with no stop-loss triggers (tightest GFS at -0.4%). What worked was the stop-loss scan and refusing to chase stale scan prices; what didn't was `research.get_bars()`, which sends no sort parameter, so the 60-bar window returned the oldest bars (through 10/05) and every scan MA was stale. Next session: fix `get_bars` before trusting any MA, and watch the five positions still over the 5% cap (ANET, LITE, MRVL, TSM, NVDA).

### 2026-10-16
No orders today. Every top-5 pick is low conviction and below its 20d MA, and none reclaimed its MA on live quotes. The routine ran late, at 13:42 research and 13:47 trading, so the 9:45 and 10:00 windows were missed again. The 10/12 lesson applies: this session is logged as a late run. Once live quotes are used, the decision was still HOLD on every name. Equity was $92,602 at 13:46 ET, down about 1.2% on the day, with no stop triggers. Tomorrow: confirm the 9:45 and 10:00 ET routines start inside their windows, and fix `get_bars` sorting before the scan MAs are trusted again.

**Close update (EOD fetch, 10/16):** Equity closed at $92,054.77 vs last_equity $93,766.83, down $1,712.06 (-1.83%). That is $598 below the 13:41 intraday mark ($92,652.60). Cash is unchanged at $56,007.36 and no orders were placed. Positions are still 8 names, with market value $36,047.41. Closing marks: GFS $46.43 (-5.1% from $48.94 entry, the tightest name, still above the 8% stop). LITE, MRVL, NVDA, TSM, and ANET remain over the 5% cap with no watchlist override, so they stay held. No new lesson: the no-trade outcome matches the existing 10/12 and 10/15 lessons. Tomorrow: check GFS against the 8% line (about $45.02) at the open.

### 2026-10-19
Closing check (16:00+): equity $92,990.31, down $94.48 from the 15:36 intraday figure ($93,084.79). Cash $56,007.36 unchanged. Every position moved against us into the close except ANET, CIEN, and LITE, which were up. GFS closed at $46.29, -5.4% from entry, still well above the $45.02 stop line. No orders were placed, which was correct: all five top-5 names were below both MAs with no reclaim. The late 15:29 research run and 15:36 trading run gave us only 30 minutes of session, so the no-trade outcome was driven by the timing constraint as much as by the signals. Watch next session: whether the SOX rout stabilizes, whether AVGO or CSCO reclaims its 20-day MA on live quotes, and whether GFS holds above $45.02. Run both routines in their 9:45 and 10:00 windows.

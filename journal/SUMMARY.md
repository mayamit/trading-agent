# Journal Summary

_Generated 2026-10-20 23:11 from 7 of 123 entries (2026-10-12 → 2026-10-20)_

## Latest Portfolio Status _(from 2026-10-20)_

- Cash: $56,007.36
- Positions: ANET (28 @ $141.86, now $181.03), CIEN (11 @ $322.10, now $343.23), GFS (80 @ $48.94, now $47.79), GLW (30 @ $130.76, now $132.74), LITE (6 @ $648.89, now $831.46), MRVL (22 @ $217.56, now $242.77), NVDA (23 @ $206.99, now $217.13), TSM (12 @ $408.61, now $427.76)
- Total Value: $93,113.69 (positions $37,106.33), up $267.78 (+0.29%) vs last_equity $92,845.91 (intraday)
- 8% stop-loss check (entry basis): no trigger. Tightest: GFS -2.4% ($47.79 vs $48.94; stop line $45.02).
- 5% cap check (of $93,113.69; cap $4,655.68): ANET 5.44%, LITE 5.36%, MRVL 5.74%, NVDA 5.36%, TSM 5.51% are over cap with no watchlist override. Held per doctrine, not trimmed, not added to. CIEN 4.06%, GLW 4.28%, GFS 4.10% are under cap.

## Recent Trades (last 7 days)

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

### 2026-10-20
_Trading routine ran 14:14 ET (late run: 10:00 window missed). Market open. Decisions on live IEX quotes (14:14 ET) and desc-sorted 20/50-day closes, not the scan MAs._

| Time | Symbol | Action | Qty | Price | Reasoning |
|------|--------|--------|-----|-------|-----------|
| 14:14 | — | NO ORDERS | — | — | All 5 top-5 picks evaluated. None met an entry rule. No substitute ticker considered. |

**Decisions (14:14 ET, live quotes, recomputed MAs):**
- **GFS** — HOLD, no add. Bid $47.79 / ask $47.84, last $47.82. Still under the 20d ($48.05). The 50d ($47.48) is below price, but the 20d reclaim is not confirmed. Add room exists (4.10% of account, cap 5%), not used. Stop line $45.02; currently -2.3% from $48.94 entry.
- **CSCO** — NO BUY. Ask $106.69, last $106.62. About 4% under both the 20d ($110.91) and 50d ($111.01). No company catalyst.
- **AVGO** — NO BUY. Bid $335.43 / ask $336.00, last $335.40. About 5% under the 20d ($352.56) and 50d ($362.12). No company news in window.
- **CIEN** — HOLD, no add. Bid $343.24 / ask $344.72. About 9.5% under the 20d ($379.54) and 8.5% under the 50d ($375.65). Position +6.8% vs entry, under cap (4.06%). Trend is broken, so no add.
- **KEYS** — NO BUY. Bid $322.40 / ask $335.94 (wide, IEX), last $335.18. Under the 20d ($363.84) and 50d ($343.77). Overbought-RSI note is stale; no fresh catalyst.

**Risk checks:**
- 8% stop-loss: no trigger. Tightest is GFS at -2.3% from entry. All other held names are above entry. No forced closes.
- Cash $56,007.36 unchanged. No new capital deployed.
- Over-cap positions (ANET, LITE, MRVL, NVDA, TSM) held per doctrine. Not trimmed, not added to. No SELL signal on any held name: none of them is a top-5 pick, and no morning thesis is broken on live data.

## Recent Reflections (last 3 days)

### 2026-10-16
No orders today. Every top-5 pick is low conviction and below its 20d MA, and none reclaimed its MA on live quotes. The routine ran late, at 13:42 research and 13:47 trading, so the 9:45 and 10:00 windows were missed again. The 10/12 lesson applies: this session is logged as a late run. Once live quotes are used, the decision was still HOLD on every name. Equity was $92,602 at 13:46 ET, down about 1.2% on the day, with no stop triggers. Tomorrow: confirm the 9:45 and 10:00 ET routines start inside their windows, and fix `get_bars` sorting before the scan MAs are trusted again.

**Close update (EOD fetch, 10/16):** Equity closed at $92,054.77 vs last_equity $93,766.83, down $1,712.06 (-1.83%). That is $598 below the 13:41 intraday mark ($92,652.60). Cash is unchanged at $56,007.36 and no orders were placed. Positions are still 8 names, with market value $36,047.41. Closing marks: GFS $46.43 (-5.1% from $48.94 entry, the tightest name, still above the 8% stop). LITE, MRVL, NVDA, TSM, and ANET remain over the 5% cap with no watchlist override, so they stay held. No new lesson: the no-trade outcome matches the existing 10/12 and 10/15 lessons. Tomorrow: check GFS against the 8% line (about $45.02) at the open.

### 2026-10-19
Closing check (16:00+): equity $92,990.31, down $94.48 from the 15:36 intraday figure ($93,084.79). Cash $56,007.36 unchanged. Every position moved against us into the close except ANET, CIEN, and LITE, which were up. GFS closed at $46.29, -5.4% from entry, still well above the $45.02 stop line. No orders were placed, which was correct: all five top-5 names were below both MAs with no reclaim. The late 15:29 research run and 15:36 trading run gave us only 30 minutes of session, so the no-trade outcome was driven by the timing constraint as much as by the signals. Watch next session: whether the SOX rout stabilizes, whether AVGO or CSCO reclaims its 20-day MA on live quotes, and whether GFS holds above $45.02. Run both routines in their 9:45 and 10:00 windows.

### 2026-10-20
Closing snapshot (equity $93,849.74, cash $56,007.36): up $1,003.83 (+1.08%) on the day vs last_equity $92,845.91, and up $736 from the $93,113.69 intraday mark in the trading entry. The drift came from a late-afternoon semis rebound on existing holdings (LITE +3.4%, MRVL +3.8%, TSM +2.6%, GFS +4.3%, CIEN +2.5%). No orders were placed, so the gain is mark-to-market only, and the no-buy calls on CSCO, AVGO and KEYS sat out the bounce without loss. Stop-loss discipline held: no position is near -8%, and the tightest, GFS, recovered to $48.10 (-1.7% vs entry). The routines ran late again (research 14:06, trading 14:14), so the top-5 was never evaluated at the open. Next session: check whether GFS holds above the 20-day (~$48.05) on live quotes, confirm the 10/15 `get_bars` sort fix is in place, and keep watching the over-cap names (MRVL 5.77%, ANET 5.53%, LITE 5.52%, TSM 5.51%, NVDA 5.41%), which are held per doctrine.

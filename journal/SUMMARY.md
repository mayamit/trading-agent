# Journal Summary

_Generated 2026-11-13 01:04 from 7 of 140 entries (2026-11-04 → 2026-11-12)_

## Latest Portfolio Status _(from 2026-11-12)_

Not recorded this session. No account pull was made because the session stopped at step 1. Last recorded status (2026-11-10 close, per `journal/SUMMARY.md`): cash $86,292.11, no open positions.

## Recent Trades (last 7 days)

### 2026-11-04
_Trading run 15:38 ET, late against the 10:00 window (lesson 2026-10-12: logged as a late session). The two stop-loss closes ran first, before any buy decision. Live IEX quotes at 15:38 ET: CIEN bid $261.10 / ask $270.55 (thin, 40x40) / last $270.19; GLW bid $116.85 / ask $117.56 / last $117.46. Sell limits set 0.2% under bid._

| Time | Symbol | Action | Qty | Price | Reasoning |
|------|--------|--------|-----|-------|-----------|
| 15:39 | CIEN | SELL | 11 | $260.58 limit; filled 11 @ $270.48 | Mandatory 8% stop. Entry $322.10, live $270.19 (-16%), through the $296.33 line. Order d90187f4-b4de-4153-8313-38351e716e3d. Realized about -$568 vs cost basis $3,543.10. |
| 15:39 | GLW | SELL | 30 | $116.62 limit; filled 30 @ $117.24 | Mandatory 8% stop. Entry $130.756, live $117.46 (-10.2%), through the $120.30 line. Order ab1077d8-2763-4d5b-8866-cfe5ae538daa. Realized about -$405 vs cost basis $3,922.68. |

**Top-5 decisions (no orders; live quotes and MAs from a desc-sorted pull of closed bars through 11/03):**
- **SOFI (low, 15% cap), NO BUY / HOLD.** Last $17.455. Recomputed 20d $15.52 and 50d $16.50, so price is above both intraday. 11/03 closed at $16.78, also above both, so the morning's "confirmed close above both MAs" condition is arguably met once. Not bought: the stock is now above the only analyst target (Truist PT $17), it is up about 4% on the day into the open, and the morning's conviction was low. A single closed bar above both MAs does not reclaim a trend that was below both for weeks (lesson 2026-10-21). Re-check at the 11/05 close.
- **COHR (low), NO BUY.** Last $192.83. Recomputed 20d $247.22 and 50d $276.38, both well above price. Earnings 11/05 is a binary event with the trend broken; no entry into the print.
- **FORM (low), NO BUY.** Last $84.85. Recomputed 20d $111.18 and 50d $115.47, both well above price. Freedom Capital upgrade alone is not an entry (lesson 2026-08-21).
- **AAOI (low), NO BUY.** Last $59.40. Recomputed 20d $82.79 and 50d $96.64, far above price. Northland upgrade without confirmation (lesson 2026-07-22).
- **CSCO (low), NO BUY.** Last $103.13. Recomputed 20d $109.67 and 50d $109.66, both above price. Managed-service launch is product news with no direct catalyst.

**Decision framework (15:39 ET):**
1. Cash: $63,623.87 before the sells, $70,116.35 after both fills.
2. Open positions after the sells: ANET, LITE, NVDA, TSM. CIEN and GLW closed.
3. News: picks are low-conviction analyst calls and product news; no buy case cleared the MA test.
4. MAs: no pick has a confirmed closed-bar trend reclaim except SOFI, which is deferred (above).
5. Risk on a missed buy: none taken. Cash stays uninvested, which is the book's current posture.

**Risk checks (15:39 ET):**
- 8% stop-loss: CIEN and GLW closed. ANET (+26%), LITE (-5.3%, stop line $596.98, live about $614.72), NVDA (-2.7%), TSM (-2.5%) are above the line. No other forced closes.
- LITE is the watch item. It trades on the Marvell all-stock deal (4.5 MRVL per LITE share), and today's drop is -9.6% intraday. Not sold; the position is above its stop, and no thesis rule was broken on the data. Re-check the MRVL level and the spread before the next session.
- Over-cap names (ANET, NVDA, TSM) stay held and blocked from adding, per the cap rule.
- Note: CIEN's sell filled at $270.48, above the $260.58 limit, consistent with the limit working as intended.

### 2026-11-05
_Filled in by the EOD routine from the Alpaca order record (orders 20:54–20:56 UTC = 15:54–15:56 ET). The trading routine did not write this section. All orders were limit orders; all are in a terminal state, with none open._

| Time | Symbol | Action | Qty | Price | Reasoning |
|------|--------|--------|-----|-------|-----------|
| 15:54 | LITE | SELL | 6 | $517.28 fill (limit $497.50) | 8% stop enforcement: -20.0% vs $648.89 entry |
| 15:55 | NVDA | SELL | 23 | $183.06 fill (limit $183.00) | 8% stop enforcement: -11.9% vs $206.99 entry |
| 15:55 | TSM | SELL | 12 | $352.85 avg (1 @ $354.41 + 11 @ $352.71) | 8% stop enforcement: -13.6% vs $408.61 entry. The first TSM order (limit $356.00) was canceled unfilled. The 403 "insufficient qty" on the retry was shares held by that pending order, not an error. |
| 15:56 | ANET | SELL | 14 | $160.13 fill (limit $159.80) | Trim half on MA breakdown: +12.9% vs $141.86 entry, below both MAs. The first ANET order (limit $160.75) was canceled unfilled. |

### 2026-11-06
| Time | Symbol | Action | Qty | Price | Reasoning |
|------|--------|--------|-----|-------|-----------|
| 15:12 | ANET | SELL | 14 | $164.82 limit; filled 14 @ $170.44 | Discretionary exit, not a stop. +19% vs $143.37 entry; below both MAs (20d $182.88, 50d $193.26). Per lesson 2026-11-04, exit the broken-trend remainder rather than default to HOLD. Order 450c5057-45bd-4759-92c3-6c52028a3c7a. |
| — | — | NO BUY | — | — | All five top-5 picks (CSCO, LASR, GFS, MRVL, NVDA) failed the entry rule on live data. No substitute ticker considered. |

### 2026-11-10
_Trading run 15:40 ET, late against the 10:00 window (lesson 2026-10-12: logged as a late session). Market open. Decisions use live IEX quotes (15:40 ET) and MAs recomputed from a desc-sorted 60-day pull that excludes today's partial bar. The morning's "last" prices and MAs were stale and are not used: e.g. LASR morning last $37.15 vs live $43.98, ALAB morning last $258.72 vs live $214.5, and the morning 20d MAs differ from the recompute (SOFI $15.43 vs $15.72; ALAB $306.52 vs $262.82)._

| Time | Symbol | Action | Qty | Price | Reasoning |
|------|--------|--------|-----|-------|-----------|
| 15:40 | — | NO ORDERS | — | — | All five top-5 picks (SOFI, LASR, ALAB, COHR, VECO) failed the entry rule on live data. No pick has a confirmed close above both MAs today. No substitute ticker considered. No held positions, so no stop or SELL review. |

**Top-5 decisions (live bid/ask/last at 15:40 ET; closed-bar MAs):**
- **SOFI (low, 15% cap), NO BUY.** Bid $16.18 / ask $16.19 / last $16.18. 20d $15.72, 50d $16.33. Price is above the 20d but back under the 50d intraday. The 11/09 close ($16.75) was above both, but that is a prior-day close, and today's trade has undone it. Morning's own gate is a confirmed close, which has not happened today. Lesson 2026-10-21 applies. Re-check at the 11/10 close.
- **LASR (low, 3% cap), NO BUY.** Last $43.98 (bid $43.50 / ask $44.09). 20d $36.47, 50d $38.47. Price is above both, and the 11/06 and 11/09 closes ($38.11, $43.24) were above the 20d. But price is about 21% over the 20d after a one-day gap from $29.29 (11/05) to $43.24 (11/09). Morning's gate was a confirmed close above the 20d, and today's close is not yet in. Chasing a gap with low conviction is the pattern in lessons 2026-06-02 and 2026-07-22. Re-check at the 11/10 close, and only enter if it holds above the 20d.
- **ALAB (low), NO BUY.** Bid $214.43 / ask $214.79 / last $214.52. 20d $262.82, 50d $299.00. About 18% under the 20d and 26% under the 50d. The 11/09 +14% earnings pop does not reclaim the trend (lesson 2026-10-30).
- **COHR (low), NO BUY.** Bid $211.27 / ask $225.57 (wide; thin-feed ask, not used, lesson 2026-10-14) / last $214.23. 20d $224.49, 50d $268.90. Price is under both. Rothschild PT raise alone is not an entry (lesson 2026-08-21).
- **VECO (low), NO BUY.** Bid $33.97 / ask $39.83 (wide, thin feed, not used) / last $39.71. 20d $41.66, 50d $44.95. Price is under both. Citi maintained Buy with a cut PT is not an entry (lesson 2026-08-21).

**Decision framework (15:40 ET):**
1. Cash: $86,292.11 before and after. No orders placed.
2. Open positions: none.
3. News: all picks are analyst or earnings headlines, and none cleared the MA test on live data.
4. MAs: only LASR and SOFI are above the 20d intraday; SOFI is under the 50d.
5. Risk on a missed buy: none taken. Cash stays uninvested, consistent with the book's posture.

### 2026-11-12
None. Session skipped (top5 missing).

## Recent Reflections (last 3 days)

### 2026-11-10
No trades, and that held up. All five top-5 names failed the entry rule on live quotes, and the morning's stale scan prices (LASR $37.15 vs $43.98 live) would have looked like entries if used. Cash stayed at $86,292.11 with no positions, and the closing account pull matches the trading session with no drift. What didn't work was timing: both the research and trading runs logged around 15:40 ET, so the 9:45 and 10:00 windows were missed (lesson 2026-10-12). Next session, check the morning run time first; if it is late, log it as a missed session and re-check SOFI's close against both MAs, since it is the only name above both on the 11/09 close.

### 2026-11-11
No trades today: the morning top-5 handoff for 11/11 was never written, so the trading session skipped by design and no orders were placed. Closing state is flat with $86,292.11 cash and no positions, unchanged from the 11/10 account pull, so there is no drift to explain. Next session: confirm `journal/top5/2026-11-12.json` exists before the 10:00 ET decision window, and check whether the 11/11 morning routine ever ran, since no `2026-11-11-morning.log` exists in the runlog. No new lesson is recorded, because this was a pipeline gap and not a market outcome.

### 2026-11-12
Two consecutive sessions (11/09 and 11/11) and now 11/12 have no top-5 handoff. The morning research pipeline is not producing `journal/top5/YYYY-MM-DD.json`, and the morning run logged at 16:06 ET is too late to fix the day. No position is open, so no 8% stop exposure exists and nothing was left unmanaged. Follow-up for the next session: confirm the morning routine fires inside its 9:45 ET window and writes the top5 file before 10:00 ET. Lessons step skipped: this is a pipeline gap, not a market outcome, so no new lesson is recorded.

### Closing-state check (EOD routine, run 2026-11-13)
Account pulled at close review: cash $86,292.11, equity $86,292.11, no open positions. This matches the last recorded status (2026-11-10 close), so there is no drift and no stop-loss exposure. The 11/12 session produced no trades. The gap is in the pipeline: no top-5 handoff has been written since 11/08, and the 11/12 morning routine ran after the close. Next session, confirm the morning research fires inside its 9:45 ET window and writes `journal/top5/YYYY-MM-DD.json` before the 10:00 ET trading window. Lessons step skipped: this is a pipeline issue already covered by the 2026-10-12 lesson, not a new market lesson.

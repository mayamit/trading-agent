# Journal Summary

_Generated 2026-10-29 23:57 from 7 of 130 entries (2026-10-21 → 2026-10-29)_

## Latest Portfolio Status _(from 2026-10-29)_

- Cash: $59,391.85
- Positions: ANET (28 @ $141.86, now $183.60), CIEN (11 @ $322.10, now $350.24), GLW (30 @ $130.76, now $128.43), LITE (6 @ $648.89, now $920.54), MRVL (22 @ $217.56, now $215.24), NVDA (23 @ $206.99, now $212.60), TSM (12 @ $408.61, now $429.54)
- Total Value: $92,540.70 (positions $33,148.85; last_equity $93,799.18)
- Risk: 8% stop-loss not triggered on any name. Tightest is GLW at -1.8% from entry (stop line $120.30). MRVL is -14.5% on the day after a Lumentum acquisition-talk report, but it is still only -1.1% from its $217.56 entry.
- 5% cap ($4,627.04 on $92,540.70): ANET 5.56%, LITE 5.97%, MRVL 5.12%, NVDA 5.28%, TSM 5.57% are over cap with no watchlist override. They stay held and are blocked from adding. CIEN 4.16% and GLW 4.16% have room.

## Recent Trades (last 7 days)

### 2026-10-21
_Trading run 14:19–14:21 ET (late: the 10:00 window was missed). Live IEX quotes at 14:19 (GFS bid $48.85 / ask $48.91 / last $48.87; the quote and last trade agree, so the ask is reliable). MAs recomputed from a desc-sorted pull of 60 daily closes._

| Time | Symbol | Action | Qty | Price | Reasoning |
|------|--------|--------|-----|-------|-----------|
| 14:20 | GFS | BUY | 15 | $48.95 limit; filled 15 @ $48.91 | Price $48.87–48.91 is above the 20d ($48.14) and 50d ($47.42), so the 10/20 "reclaim the 20d" condition holds on live data. Fresh company news: EUR 1.1B Dresden expansion (10/19). Medium conviction. Sized to stay under the 5% cap: position goes from 80 to 95 shares, about 4.95% of $93,900 (cap $4,695). Order 6cdc1527-1090-45db-9c9a-64b9dfbb12d9. Stop line $45.02. |

**Decisions on the other four picks (HOLD / no buy):**
- **SOFI (low):** Bid $14.99 / ask $15.00, last $15.005. Under the 20d ($15.48) and 50d ($16.88). The Prudential partnership is a product news item with no price confirmation (lesson 2026-07-22). No buy.
- **CSCO (low):** Bid $107.49 / ask $107.50. Under the 20d ($110.96) and 50d ($110.75). Product report, no catalyst. No buy.
- **KEYS (low):** Bid $343.47 / ask $345.02, last $343.61. Sits on the 50d ($343.74) and is 7.6% under the 20d ($363.30). The news is unrelated to KEYS. MA support alone is not an entry (lesson 2026-10-20). No buy.
- **FN (low):** Bid $358.75 / ask $359.47, last $358.95. About 16% under the 20d ($425.46) and 50d ($431.36). Analyst action with no technical confirmation (lesson 2026-08-21). No buy.

**Note:** `validate_order()` checks only the order's own value against the cap, not the position's total. The 5% check for GFS was done by hand above.

### 2026-10-22
| Time | Symbol | Action | Qty | Price | Reasoning |
|------|--------|--------|-----|-------|-----------|
| 14:14 | GFS | SELL | 95 | $43.00 limit; filled 95 @ $43.35 | 8% stop-loss breach at -11.4% from $48.935 entry. The 10/20 reclaim thesis failed. Full close per CLAUDE.md. Order 45f21a55-cbcd-4490-a0b6-21b2fe6bddb1. |

### 2026-10-23
| Time | Symbol | Action | Qty | Price | Reasoning |
|------|--------|--------|-----|-------|-----------|
| after 14:03 | — | NO ORDERS | — | — | All 5 top-5 picks checked on live IEX quotes and desc-sorted 20/50-day closes. None met an entry rule. No substitute ticker considered. |

**Decisions (live check, shortly after the 14:03 ET market-status pull; late run: the 10:00 window was missed):**
- **KEYS (medium) — HOLD / no buy.** Bid $302.55 / ask $316.34 / last $316.25. Below the 20d ($358.60) and 50d ($342.10). The scan's "bullish MA stack" read does not hold on live data. The KTL test selection is a real company item, but price is about 12% under the 20d and under the 50d, so it fails the "live price above both MAs" condition the morning set.
- **MTSI (low) — HOLD / no buy.** Bid $225.49 / ask $247.80 (wide, IEX) / last $237.46. Below the 20d ($292.40) and 50d ($280.45). The only news is the Nov 5 earnings date, so there is no catalyst today and the technical premise is broken.
- **FN (low) — HOLD / no buy.** Bid $315.37 / ask $334.50 (wide, IEX) / last $315.97. About 24% under the 20d ($416.20) and 25% under the 50d ($421.20). Sector-only news with no company catalyst (lesson 2026-08-21).
- **CSCO (low) — HOLD / no buy.** Bid $106.24 / ask $106.27 / last $106.29. Under the 20d ($110.83) and 50d ($110.22). Headline is not about Cisco (lesson 2026-07-22).
- **VIAV (low) — HOLD / no buy.** Bid $31.20 / ask $31.23 / last $31.235. Under the 20d ($40.29) and 50d ($38.58). Macro headline only, and the trend is broken (lesson 2026-10-21: no entry on a stale bullish read).

**Scan reliability:** All five picks carried a bullish MA read in the morning top-5, yet on live data all five trade below both their 20d and 50d MAs, and their scan prices were 19–28% off live quotes. The morning top-5 is not usable as a buy list until the scan's price and MA inputs are fixed (see lessons 2026-10-08 and 2026-10-15).

**Risk checks (live pull):**
- 8% stop-loss: no trigger. Tightest is GLW at -4.3% from its $130.76 entry (last $125.09). ANET, LITE, MRVL, NVDA, TSM and CIEN are above entry. No forced closes.
- SELL signals: none. No held name is in today's top 5, and none is at the -8% line.
- Cash $59,391.85 unchanged. No new capital deployed.
- Over-cap names (ANET, LITE, MRVL, NVDA, TSM) stay held and blocked from adding, per the cap rule.

### 2026-10-26
| Time | Symbol | Action | Qty | Price | Reasoning |
|------|--------|--------|-----|-------|-----------|
| 15:41 | — | NO ORDERS | — | — | All 5 top-5 picks checked on live IEX quotes and recomputed 20/50-day closes (desc-sorted pull). None met the entry rule (live close above both MAs). No substitute ticker considered. |

**Decisions (15:41 ET, live quotes; late run, 19 minutes before the close):**
- **GFS (low) — NO BUY.** Bid $43.63 / ask $45.52 / last $45.55. Recomputed 20d $47.56 and 50d $46.86, so price is about 4% under the 20d and under the 50d. The 10/22 stop-out was a failed reclaim, and there is no confirmed close above either MA (lesson 2026-10-21).
- **CIEN (low) — HOLD, no add.** Last $337.82. Recomputed 20d $375.79 and 50d $368.65, so the trend is broken. The +4.9% gain on the position is above entry, and the add room is about 2 shares before the cap. The reaffirmed Buy is not a fresh catalyst.
- **SOFI (low) — NO BUY.** Last $14.44. Recomputed 20d $15.20 and 50d $16.66, both above price. Initiation alone is not an entry (lesson 2026-08-21).
- **ALAB (low) — NO BUY.** Last $261.68. Recomputed 20d $321.02 and 50d $309.55, both above price. The rebound is sector-only, and the last close ($262.24) is not a reclaim.
- **FORM (low) — NO BUY.** Last $101.73. Recomputed 20d $125.51 and 50d $118.07, both above price. Facility news does not offset the broken trend.

**Risk checks (15:41 ET):**
- 8% stop-loss: no trigger. Tightest is GLW at -2.2% from its $130.76 entry (last $127.87). All other held names are above entry. No forced closes.
- SELL signals: none. No held name's morning thesis is broken on the data, and none is at the -8% line.
- Cash $59,391.85 unchanged. No new capital deployed.
- Over-cap names (ANET, LITE, MRVL, NVDA, TSM) stay held and blocked from adding, per the cap rule.

### 2026-10-27
| Time | Symbol | Action | Qty | Price | Reasoning |
|------|--------|--------|-----|-------|-----------|
| 15:10 | — | NO ORDERS | — | — | All 5 top-5 picks checked on live IEX quotes and recomputed 20/50-day closes (desc-sorted pull). None met its entry rule (live close above both MAs, or a confirmed reclaim). No substitute ticker considered. |

_Trading run 15:10 ET, late against the 10:00 window. Market open, closes 16:00. Decisions below use live quotes, not the morning scan prices._

**Decisions (15:10 ET, live IEX quotes; bid/ask/last and recomputed MAs):**
- **AVGO (low), HOLD / no buy.** Last $342.49 (bid $342.45 / ask $342.50). Recomputed 20d $347.10 and 50d $354.49, so price is under both. The Anthropic IPO headline and PT raise are not enough without a live reclaim.
- **MTSI (low), NO BUY.** Last $258.09 (bid $257.30 / ask $258.37). Recomputed 20d $289.18 and 50d $277.54, both above price. The upgrade alone is not an entry (lessons 2026-07-22, 2026-08-21).
- **CIEN (low, held), HOLD, no add.** Last $352.25 (bid $351.79 / ask $369.22, wide). Recomputed 20d $375.54 and 50d $366.75, both above price, so the trend is broken. The position is +9.3% vs entry ($322.10). The reaffirmed Buy is not a fresh catalyst. Add room is about 2 shares, not used.
- **KEYS (low), NO BUY.** Last $334.39 (bid $325.00 / ask $349.18, wide). Recomputed 20d $355.50 and 50d $340.90, so price is under the 20d and under the 50d. The 6G-ROCKET news has no direct catalyst (lesson 2026-10-20).
- **GFS (low, re-entry), NO BUY.** Last $46.50 (bid $46.39 / ask $46.53). Recomputed 20d $47.46 and 50d $46.71, so price is under both. No confirmed close above either MA (lesson 2026-10-21).

**Risk checks (15:10 ET):**
- 8% stop-loss: no trigger. Tightest is GLW at -2.8% from its $130.76 entry (last $127.03; stop line $120.30). ANET, CIEN, LITE, MRVL, NVDA and TSM are above entry. No forced closes.
- SELL signals: none. No held name's morning thesis is broken on the morning data, and none is at the -8% line.
- Cash $59,391.85 unchanged. No new capital deployed.
- Over-cap names (ANET, LITE, MRVL, NVDA, TSM) stay held and blocked from adding, per the cap rule.

### 2026-10-28
| Time | Symbol | Action | Qty | Price | Reasoning |
|------|--------|--------|-----|-------|-----------|
| 15:20 | — | NO ORDERS | — | — | All 5 top-5 picks checked on live IEX quotes and a desc-sorted 20/50-day pull (84 bars). None met its entry rule (confirmed close above both MAs, or a confirmed reclaim). No substitute ticker considered. Late run: the 10:00 window was missed. |

**Decisions (15:20 ET, live quotes; the morning scan's MAs and prices are not used):**
- **MTSI (low), NO BUY.** Last $258.65 (bid $256.74 / ask $273.97, wide). Recomputed 20d $287.81 and 50d $276.83, so price is under both. The 10/27 upgrade alone is not an entry (lessons 2026-07-22, 2026-08-21).
- **ALAB (low), NO BUY.** Last $296.46 (bid $283.00 / ask $313.83, wide). Recomputed 20d $314.36 and 50d $308.69, both above price. The 10/27 key signal did not hold into the close.
- **SOFI (low, 15% cap), NO BUY.** Last $16.87 (bid $16.88 / ask $16.89). This is the one pick that now trades above both recomputed MAs (20d $15.28, 50d $16.61). The move is an earnings gap on Q3 results and raised PTs (Scotiabank $26, StoneX $27, TD Cowen Hold $18), up about 18% from the morning's $14.29. It is intraday, with no confirmed close above either MA, and an earnings gap chased at the 15% cap is the failure mode in lessons 2026-10-21 and 2026-07-16. Re-check at the next close. Still not a buy this session.
- **GFS (low, re-entry), NO BUY.** Last $45.53 (bid $45.50 / ask $45.54). Recomputed 20d $47.35 and 50d $46.63, so price is under both. No confirmed reclaim (lesson 2026-10-21).
- **CIEN (low, held), HOLD, no add.** Last $362.60 (ask $379.94 is a thin-feed quote, not used; lesson 2026-10-14). Recomputed 20d $376.03 and 50d $365.86. Price is under the 20d and above the 50d, so the trend is still mixed. The position is +12.6% vs $322.10 entry. Add room is about 1 share under the 5% cap, not used.

**Risk checks (15:20 ET):**
- 8% stop-loss: no trigger. Tightest is GLW at +1.4% from its $130.76 entry (last $132.56). All held names are above entry. No forced closes.
- SELL signals: none. No held name's thesis is broken on live data, and none is at the -8% line.
- Cash $59,391.85 unchanged. No new capital deployed.
- Over-cap names (ANET, LITE, MRVL, NVDA, TSM) stay held and blocked from adding, per the cap rule.

### 2026-10-29
Trading run 15:22 ET, late against the 10:00 window. Market open, closes 16:00. Decisions use live IEX quotes (bid/ask/last) and a desc-sorted 20/50-day pull that excludes today's partial bar. The morning scan's MAs and prices are not used.

| Time | Symbol | Action | Qty | Price | Reasoning |
|------|--------|--------|-----|-------|-----------|
| 15:22 | — | NO ORDERS | — | — | All 5 top-5 picks checked. None met its entry rule (confirmed close above both MAs, or a confirmed reclaim). No substitute ticker considered. |

**Decisions (15:22 ET, live quotes; closed-bar MAs):**
- **SOFI (low), NO BUY.** Last $17.53 (bid $17.52 / ask $17.53). Recomputed 20d $15.38 and 50d $16.60, so intraday it is above both. That is not a confirmed close, and the move is an earnings gap with PT raises (lesson 2026-10-21). Re-check at the next close. Not a buy this session.
- **CIEN (low, held), HOLD, no add.** Last $349.91 (bid $348.71 / ask $350.06). Recomputed 20d $374.57 and 50d $364.87, so price is under both. The position is +8.6% vs $322.10 entry. The AllianceBernstein reaffirmation is not a fresh catalyst. Add room is about 1 share, not used.
- **KEYS (low), NO BUY.** Last $329.08 (bid $318.06 / ask $329.41). Recomputed 20d $351.93 and 50d $341.02, both above price. The 6G demo has no direct catalyst (lesson 2026-10-20).
- **FORM (low), NO BUY.** Last $97.50 (bid $93.19 / ask $97.76). Recomputed 20d $119.53 and 50d $116.80, both above price. The TD Cowen Hold is not enough (lesson 2026-08-21).
- **ALAB (low), NO BUY.** Last $286.99 (bid $285.30 / ask $287.36). Recomputed 20d $310.91 and 50d $308.67, both above price. The 10/27 signal did not hold.

**Risk checks (15:22 ET):**
- 8% stop-loss: no trigger. Tightest is GLW at -1.6% from its $130.76 entry (last $128.68; stop line $120.30). All other held names are at or above entry.
- SELL signals: none. MRVL fell about 14% on a Benzinga report (10/29) that Marvell is in talks to acquire Lumentum. That is an unconfirmed report, not a thesis break, and MRVL is -1% from its $217.56 entry, well inside the -8% line. Held and reviewed; no sell. Re-check if the deal is confirmed or the stock closes below the stop line ($200.16).
- Cash $59,391.85 unchanged. No new capital deployed.
- Over-cap names (ANET, LITE, MRVL, NVDA, TSM) stay held and blocked from adding, per the cap rule.

## Recent Reflections (last 3 days)

### 2026-10-27
No orders was the right call: all five top-5 picks (AVGO, MTSI, CIEN, KEYS, GFS) failed their entry rules on live quotes at 15:10, and no 8% stop triggered. The book gained about 1.2% on the session (equity $91,994.20 → $93,091.39), led by LITE and ANET, but the 14:59 research run left no morning window to act on. Since the 15:10 snapshot, equity is down $59.78 (-0.06%) on drift: GLW closed at $126.01 (-3.6% vs $130.76 entry, 4.7% above the $120.30 stop line) is the name to watch. The five over-cap names (ANET, LITE, MRVL, NVDA, TSM) stay held and blocked from adding. Next session: check GLW against its stop at the open, require a close (not an intraday touch) above both MAs before any AVGO or MTSI buy, and run research by 9:45 ET.

### 2026-10-28
No orders, as intended: all five picks failed their entry rules on live quotes, and the late run (research 15:07, decisions 15:20) missed the 10:00 window. Closing equity is $93,395.46, down $398.89 from the 15:20 snapshot and up 0.33% on the day against last_equity $93,090.18. The whole drift came from position marks, since cash held at $59,391.85. LITE (+14.6% today, +53% vs entry) carried the book, and MRVL (-5.5% today, +5.8% vs entry) was the weakest mark among names with room above the stop. Next session: confirm whether SOFI closed above both MAs before any entry, run research and trading inside their windows, and do not add to the five names still over the 5% cap. GLW is the closest to its stop line at -1.7% vs $130.76 entry ($120.30 line).

### 2026-10-29
Closing equity is $91,508.35 (cash $59,391.85, positions $32,116.50). That is down $2,290.83 (-2.4%) from the prior close and $1,032 below the 15:22 trading-session mark of $92,540.70. No orders was the right call given the session's rules, but the drift came from the held book. MRVL closed down about 17% on the day (now -4.0% from its $217.56 entry) on an unconfirmed Lumentum acquisition-talk report, and GLW is at $122.57 (-6.3% from entry), only about 1.9% above the $120.30 stop line. Tomorrow: first check GLW against $120.30 (a close below it triggers the 8% sell without discretion), then check whether the Lumentum talks were confirmed or denied and whether MRVL holds $200.16. Positions still over the 5% cap (ANET, LITE, MRVL, NVDA, TSM) stay blocked from adding.

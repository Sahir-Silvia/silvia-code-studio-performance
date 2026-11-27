# Daily Log — Silvia Code Studio

Append-only. One entry per day: what was uploaded or verified, the result, and the next step. No code in this repo.

## 2026-11-24 — Day 1

- **Inventory completed:** 17 families inventoried, ~92 compiled versions on disk, 56 successful (compile 0/0 + backtest/execution). Full inventory in the private working files.
- **Public repo created:** `silvia-code-studio-performance` — README + PERFORMANCE.md (7 verified winners) + this log.
- **Private repo #1 uploaded:** `crash-m1-ema-cross-v36` (Private) — EMA Cross EA v3.6 + v3.6.3-E, with `.mq5`, `.ex5`, best `.set` files and backtest reports.
  - Crash M1, 2026-01-01 → 2026-11-16, $10,000: **+$358.52 laptop / +$351.76 VM, 6,829 trades, 72.05% win, PF 1.101, MaxDD $121.10** (in-sample only).
- **Private repo #2 uploaded (same day):** `gold-m30-combo10-flip-v45` (Private) — Combo10 Flip EA v4.5, Gold M30, with `.mq5`, `.ex5`, best `.set` and backtest reports.
  - XAUUSDmicro M30, 2026, $10,000: **+$216.02, 429 trades, 44.99% win, PF 1.355, MaxDD $38.65** (in-sample only).
- **Next:** Private repo #3 `halftrend-boom-h4-singleind` (Boom H4, +$444.09 laptop).

## 2026-11-25 — Day 2

- **New-build check (before picking the item):** Combo10 Pro series found — `SteadymoveHalfTrendPro` + `SteadymoveSuperTrendPro` (indicators, `~/workspace/goals/mql5-profile-value/combo10-pro-series/`). v1.00 compiled 0 errors / 0 warnings with non-repaint execution evidence (EURUSD H1 snapshots A/B byte-identical). BUT: GPT review v1.00 (25 Nov ~08:50 PKT) verdict **AMEND AND RESUBMIT** (MTF closed-bar commitment defect, panel fix partial, SuperTrend ATR recovery wrong) and a v1.01 fix is in progress — the `.mq5` files on disk no longer match the REPORT.md md5s (mid-edit) while the `.ex5` files still match v1.00. **NOT appended to the queue yet** — v1.01 will be appended once it compiles 0/0 with re-QA evidence. Risk Reward v1.09 (25 Nov 02:25) and Chart Info Panel revisions are updates to already-queued items (Day 5 / Day 8), not new builds.
- **Private repo #3 uploaded:** `halftrend-boom-h4-singleind` (Private) — SingleInd HalfTrend EA v1.0, Boom 500 H4, with `.mq5`, `.ex5`, three `.set` files (best: rollover 256), matrix report and tester artefacts.
  - Boom 500 H4, 2026-01-01 → 2026-11-16, $10,000: **+$444.09 laptop / +$419.84 VM, 203 trades, 55.67% win, PF 1.59, MaxDD $75.51** (in-sample only). Rollover sweep N=256: +$470.66, 176 trades, PF 1.934.
- **Next:** Private repo #4 `stc-hull-crash-h4-singleind` (Crash H4, +$258.61 laptop).

## 2026-11-26 — Day 3

- **New-build check (before picking the item):** scanned the sr-reverse-ea folder and MQL5 goal folders — the only new .mq5 files are 7 diagnostic/probe scripts for the MQL5 article project (project-v5: PanelProbe, VerifyC10P1, ReattachC10P1, ValidateInputs, MoneyCheck, ExportBuffers, MTFBoundary) — no .ex5, no backtest, no compile report. Diagnostic files are excluded per inventory rules, so **nothing was appended to the queue**.
- **Private repo #4 uploaded:** `stc-hull-crash-h4-singleind` (Private) — SingleInd STC-Hull EA v1.0, Crash 500 H4, with `.mq5`, `.ex5`, three `.set` files (best: rollover 31), matrix report and tester artefacts.
  - Crash 500 H4, 2026-01-01 to 2026-11-16, $10,000: **+$258.61 laptop / +$242.32 VM, 258 trades, 52.33% win, PF 1.45, MaxDD $57.18** (in-sample only). Rollover sweep N=31: +$248.05, 257 trades, PF 1.432.
- **Next:** Private repo #5 `gold-h1-combo10-flip-v45` (Gold H1 cb0, +$248.86, thin-sample flag).

## 2026-11-27 — Day 4

- **New-build check (before picking the item):** scanned the sr-reverse-ea folder and MQL5 goal folders — the newest .mq5 files are the same 7 diagnostic/probe scripts for the MQL5 article project (project-v5: PanelProbe, VerifyC10P1, ReattachC10P1, ValidateInputs, MoneyCheck, ExportBuffers, MTFBoundary, 26 Nov 01:43–01:58) already noted on Day 3 — no .ex5, no backtest, no compile report. Nothing new since Day 3, so **nothing was appended to the queue**.
- **Private repo #5 uploaded:** `gold-h1-combo10-flip-v45` (Private) — Combo10 Flip EA v4.5, Gold H1 cb0 optimisation, with `.mq5`, `.ex5`, `Gold-H1-v45.set`, H1 + summary backtest reports, README, and `tester-results-cb0-optimised/` (6 CSVs: trade / signals / daily, h1 + h2).
  - XAUUSDmicro H1, 2026, $10,000: **+$248.86, 152 trades, 47.37% win, PF 1.803, MaxDD $60.17** (in-sample only). Thin-sample flag: GPT picks M30 first (429 trades, net/DD 5.59 vs H1 4.14). cb0 = TIME-CLOSE OFF, pure flip-only.
- **PERFORMANCE.md:** no change needed — the Gold H1 cb0 row (+$248.86, 152 trades, MaxDD $60.17) was already in the table since Day 1.
- **Next:** Private repo #6 `risk-reward-ratio-indicator` (28 Nov).

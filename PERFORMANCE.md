# Performance — Silvia Code Studio

All numbers: MT5 Strategy Tester, every tick based on real ticks, $10,000 demo deposit, 2026-01-01 to 2026-11-10/16 unless stated. **In-sample 2026 only. Never traded live.**

## Verified winners

| Code | Symbol / TF | Dates | Net | Trades | Win % | PF | MaxDD | Source |
|---|---|---|---|---|---|---|---|---|
| Crash M1 EMA Cross v3.6 | Crash 500, M1 | 2026-01-01 → 2026-11-16 | +$358.52 laptop / +$351.76 VM | 6,829 / 6,697 | 72.05% / 71.06% | 1.101 | $121.10 | BACKTEST-REPORT-EMA-CROSS-v3.6-CRASH500-M1-152-7.md |
| Crash M1 EMA Cross v3.6.3-E | Crash 500, M1 | to 2026-11-16 | +$159.81 | 745 | 62.68% | 1.321 | $28.25 | EMA-CROSS-V363-OPTIMIZATION-REPORT.md |
| Gold M30 Combo10 Flip v4.5 | XAUUSDmicro, M30 | 2026 | +$216.02 | 429 | 44.99% | 1.355 | $38.65 | BACKTEST-REPORT-v4.5-GOLD-SUMMARY.md |
| Gold H1 Combo10 Flip v4.5 (cb0) | XAUUSDmicro, H1 | 2026 | +$248.86 | 152 | — | — | $60.17 | GOLD-v4.5-optimization-report.md (Phase 3) |
| HalfTrend Boom H4 (SingleInd) | Boom 500, H4 | 2026 | +$444.09 laptop / +$419.84 VM | 203 | 55.67% | 1.59 | $75.51 | SINGLEIND-MATRIX-REPORT.md |
| STC-Hull Crash H4 (SingleInd) | Crash 500, H4 | 2026 | +$258.61 laptop / +$242.32 VM | 258 | 52.33% | 1.45 | $57.18 | SINGLEIND-MATRIX-REPORT.md |
| STC-Hull Step M15 (SingleInd) | Step Index, M15 | 2026 | +$820.00 | 3,668 | 48.66% | 1.069 | $494.90 | SINGLEIND-MATRIX-REPORT.md — high-drawdown caveat, net/DD 1.66 |

## Recorded failures (for honesty)

| Code | Result | Note |
|---|---|---|
| Universal Trend Scalper Config E | +$1,889.30 in-sample, **−$441.10 out-of-sample** | Edge did not survive out-of-sample. Dead. |
| EMA Cross v3.7 (true closed-bar cross) | −$954.38 | The documented cross loses; v3.6's edge is the forming-bar cross. |
| SuperTrend EA (Step, all TFs) | M5 −$150.10 (least loss) to M1 −$2,379.10 | No profitable variant in 36-combo auto-close test. |
| SR Reverse EA v1.0–v2.6 | All losing overall | Pattern search closed. |
| Combo10 Flip v4.4 (Crash/Boom) | Losing | Live H4 attach stopped 19 Nov 2026, 0 trades. |

## Method note

VM-compiled `.ex5` files are AVX2-only and do not run on X64-only machines. Recompile the `.mq5` on your own machine with MetaEditor F7. No profit is guaranteed by any backtest.

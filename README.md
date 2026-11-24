# Silvia Code Studio — Performance

Public performance and daily working log of **Silvia Code Studio** (GitHub: Sahir-Silvia).

**No source code in this repo — ever.** All EA / indicator code lives in separate Private repos. This repo shows only verified results and daily progress, so anyone can see what was built and how it performed, without seeing the code.

## Verified winners (MT5 Strategy Tester, in-sample 2026 only)

| Code | Symbol / TF | Net profit | Trades | Win rate | Max drawdown |
|---|---|---|---|---|---|
| Crash M1 EMA Cross v3.6 | Crash 500, M1 | **+$358.52** laptop / +$351.76 VM | 6,829 | 72.05% | $121.10 |
| Gold M30 Combo10 Flip v4.5 | XAUUSDmicro, M30 | **+$216.02** | 429 | 44.99% | $38.65 |
| Gold H1 Combo10 Flip v4.5 (cb0) | XAUUSDmicro, H1 | **+$248.86** | 152 | — | $60.17 |
| HalfTrend Boom H4 (SingleInd) | Boom 500, H4 | **+$444.09** laptop / +$419.84 VM | 203 | 55.67% | $75.51 |
| STC-Hull Crash H4 (SingleInd) | Crash 500, H4 | **+$258.61** laptop / +$242.32 VM | 258 | 52.33% | $57.18 |
| EMA Cross v3.6.3 Setting E | Crash 500, M1 | **+$159.81** | 745 | 62.68% | $28.25 |

See `PERFORMANCE.md` for the full table with profit factor, dates, deposit and sources.

## Honest caveats

- Every profit number above is **in-sample 2026 only, from the MT5 Strategy Tester** (every tick based on real ticks, $10,000 demo deposit).
- **Never traded live.** No out-of-sample confirmation, except where a failure is explicitly recorded (e.g. Universal Trend Scalper Config E: +$1,889.30 in-sample, −$441.10 out-of-sample — dead).
- Losing backtests are recorded too, in `PERFORMANCE.md`. A backtest profit is not a promise of future profit.

## Daily working

See `DAILY-LOG.md` — one entry per day: what was uploaded or verified that day, the backtest result, and the next step.

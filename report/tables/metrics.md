# Metrics (Val vs Test)
## LightGBM quantile (P10/P50/P90)
| Metric | Val | Test |
|---|---:|---:|
| Pinball mean | 20.4541 | 27.1850 |
| MAE (P50) | 63.77 | 80.20 |
| RMSE (P50) | 89.03 | 113.68 |
| Coverage 80% | 0.693 | 0.610 |
| Avg width 80% | 170.59 | 170.37 |

## Persistence baseline (t-48, residual-quantile)
| Metric | Val | Test |
|---|---:|---:|
| Pinball mean | 146.0898 | 164.1979 |
| MAE (P50) | 422.74 | 465.79 |
| RMSE (P50) | 603.16 | 694.40 |
| Coverage 80% | 0.809 | 0.786 |
| Avg width 80% | 1431.67 | 1431.67 |
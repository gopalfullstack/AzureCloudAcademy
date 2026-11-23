# Day 42 – Cost Forecasting and Backtesting

**Module:** 06 – AI Agents, Anomaly Detection and Predictive FinOps  
**Programme day:** 42  
**Duration:** 3.5 hours

## Learning objective

Create 7-, 14- and 30-day cost forecasts and evaluate them against a baseline.

## Detailed topics

1. Time-series structure
2. trends and seasonality
3. missing dates
4. outliers
5. naive baseline
6. moving average
7. exponential smoothing concepts
8. regression overview
9. forecast horizon
10. rolling backtest
11. MAE and RMSE
12. prediction intervals
13. uncertainty
14. refresh cadence
15. model limitations.

## Where to learn

- [Statsmodels forecasting](https://www.statsmodels.org/stable/tsa.html)
- [Forecasting principles](https://otexts.com/fpp3/)
- [Scikit-learn MAE](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.mean_absolute_error.html)

## Hands-on practical lab

Forecast daily spend for 7, 14 and 30 days using synthetic history. Compare with a naive last-value or seasonal baseline using a time-based holdout. Report error and explain uncertainty.

## Expected deliverables

- [ ] Forecast script/notebook
- [ ] backtest results
- [ ] MAE/RMSE
- [ ] forecast chart
- [ ] limitations note.

## Completion checklist

- [ ] Uses time-based validation
- [ ] compares against baseline
- [ ] forecast horizon is labelled
- [ ] uncertainty is not presented as certainty.

## Suggested session timetable

| Activity | Time |
|---|---:|
| Concepts and design | 45 min |
| Instructor demonstration | 45 min |
| Guided implementation | 60 min |
| Independent lab and evaluation | 45 min |
| Review and questions | 15 min |
| **Total** | **3.5 hours** |

**Safety requirement:** The agent is read-only. Do not give it unrestricted Azure credentials or allow it to approve or execute its own optimisation recommendations. Record evidence, uncertainty and human approval requirements.

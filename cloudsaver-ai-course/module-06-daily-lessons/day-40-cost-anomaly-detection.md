# Day 40 – Cost Anomaly Detection

**Module:** 06 – AI Agents, Anomaly Detection and Predictive FinOps  
**Programme day:** 40  
**Duration:** 3.5 hours

## Learning objective

Detect unusual spend changes and measure detector quality.

## Detailed topics

1. Anomaly definitions
2. baseline windows
3. absolute and percentage thresholds
4. moving averages
5. rolling standard deviation
6. seasonality and weekday patterns
7. statistical outliers
8. sensitivity
9. false positives/negatives
10. severity
11. alert deduplication
12. precision/recall
13. labelled test data.

## Where to learn

- [Azure Cost Management anomaly detection](https://learn.microsoft.com/en-us/azure/cost-management-billing/understand/analyze-unexpected-charges)
- [Pandas rolling windows](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.rolling.html)
- [Scikit-learn metrics](https://scikit-learn.org/stable/modules/model_evaluation.html)

## Hands-on practical lab

Create synthetic daily spend data with known injected spikes and normal seasonal variation. Implement a threshold and rolling-baseline detector. Measure precision/recall and inspect false positives and missed events.

## Expected deliverables

- [ ] Python detector
- [ ] synthetic labelled dataset
- [ ] evaluation table
- [ ] anomaly explanations.

## Completion checklist

- [ ] Detects injected spikes
- [ ] reports false positives and misses
- [ ] baseline window and thresholds are documented
- [ ] anomalies include supporting data.

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

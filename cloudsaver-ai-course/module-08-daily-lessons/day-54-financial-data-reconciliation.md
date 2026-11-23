# Day 54 – Financial Data Validation and Reconciliation

**Module:** 08 – Security, Testing, Integration and Final Product Development  
**Programme day:** 54  
**Duration:** 3.5 hours

## Learning objective

Prove that CloudSaver's reported totals agree with the selected source export.

## Detailed topics

1. Source-to-target reconciliation
2. date and billing period
3. currency consistency
4. credits/refunds/adjustments
5. duplicate and missing records
6. aggregation accuracy
7. resource attribution completeness
8. data freshness
9. lineage
10. exclusions
11. tolerance thresholds
12. evidence pack.

## Where to learn

- [Understand Cost Management fields](https://learn.microsoft.com/en-us/azure/cost-management-billing/automate/understand-usage-details-fields)
- [Azure Cost Management exports](https://learn.microsoft.com/en-us/azure/cost-management-billing/costs/tutorial-export-acm-data)
- [Pandas testing](https://pandas.pydata.org/docs/reference/api/pandas.testing.assert_frame_equal.html)

## Hands-on practical lab

Choose a sample source export and reconcile row counts and totals through raw, validated and curated stages. Explain credits, adjustments and any exclusions. Generate a report of differences and reasons.

## Expected deliverables

- [ ] Reconciliation script
- [ ] source-to-target totals
- [ ] exception report
- [ ] lineage and currency notes.

## Completion checklist

- [ ] Input count equals accepted plus rejected
- [ ] aggregate totals reconcile within documented rules
- [ ] differences are explained, not hidden
- [ ] currency and period are visible.

## Suggested session timetable

| Activity | Time |
|---|---:|
| Concepts and review | 45 min |
| Instructor demonstration | 45 min |
| Guided implementation | 60 min |
| Independent lab and validation | 45 min |
| Review and questions | 15 min |
| **Total** | **3.5 hours** |

**Product safety:** Use synthetic or explicitly authorised data. Keep production write actions disabled in the training MVP. Record limitations and require human approval for any future operational change.

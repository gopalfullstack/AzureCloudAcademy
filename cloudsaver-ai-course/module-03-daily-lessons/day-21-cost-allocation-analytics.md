# Day 21 – Cost Allocation and Analytics

**Module:** 03 – FinOps Analytics and Database Engineering  
**Programme day:** 21  
**Duration:** 3.5 hours

## Learning objective

Create allocation and variance reports that make costs understandable by owner and workload.

## Detailed topics

1. Daily/weekly/monthly aggregation
2. subscription and service breakdowns
3. resource group analysis
4. tag-based allocation
5. missing owner/environment tags
6. shared costs
7. showback
8. budget versus actual
9. variance amount and percent
10. top contributors
11. period comparison
12. unit cost
13. completeness indicators
14. allocation assumptions.

## Where to learn

- [FinOps allocation](https://www.finops.org/framework/capabilities/allocation/)
- [Azure cost analysis](https://learn.microsoft.com/en-us/azure/cost-management-billing/costs/quick-acm-cost-analysis)
- [PostgreSQL aggregate functions](https://www.postgresql.org/docs/current/functions-aggregate.html)

## Hands-on practical lab

Implement SQL views and Python reports for costs by subscription, service, resource group and owner. Flag unallocated spend and calculate budget variance. Document allocation rules for shared resources.

## Expected deliverables

- [ ] SQL views
- [ ] Python report
- [ ] allocation policy notes
- [ ] unallocated spend report.

## Completion checklist

- [ ] Allocated totals reconcile to source totals
- [ ] shared-cost assumptions are explicit
- [ ] missing tags are visible
- [ ] percentage variance handles zero budgets safely.

## Suggested session timetable

| Activity | Time |
|---|---:|
| Concepts and explanation | 45 min |
| Instructor demonstration | 45 min |
| Guided implementation | 60 min |
| Independent lab | 45 min |
| Review and questions | 15 min |
| **Total** | **3.5 hours** |

**Data safety:** Use synthetic or explicitly authorised billing data. Keep database credentials outside source control and document data currency, period, scope and lineage.

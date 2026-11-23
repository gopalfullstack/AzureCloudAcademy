# Day 9 – Azure Cost Management and Exports

**Module:** 02 – Microsoft Azure Cloud and Data Engineering  
**Programme days:** 09  
**Duration:** 3.5 hours

## Learning objective

Understand the billing data that CloudSaver will ingest and report.

## Detailed topics

1. Cost Management scopes
2. billing account/profile/invoice concepts where applicable
3. actual versus amortised cost
4. usage date and billing period
5. cost dimensions and granularity
6. Cost Analysis filters and grouping
7. scheduled exports
8. export destinations and file formats
9. schema inspection
10. credits, refunds, adjustments and currency
11. refresh latency and reconciliation.

## Where to learn

- [Cost Management overview](https://learn.microsoft.com/en-us/azure/cost-management-billing/costs/overview-cost-management)
- [Create and manage exports](https://learn.microsoft.com/en-us/azure/cost-management-billing/costs/tutorial-export-acm-data)
- [Cost details fields](https://learn.microsoft.com/en-us/azure/cost-management-billing/automate/understand-usage-details-fields)

## Instructor-led practical lab

Download an authorised export or use instructor-provided synthetic data. Inspect the schema, identify fields needed for daily spend and resource attribution, distinguish usage date from billing period, and document how credits and adjustments appear.

## Expected deliverables

- [ ] A field dictionary
- [ ] sample export
- [ ] scope/period/currency notes
- [ ] mapping from source columns to CloudSaver fields.

## Completion checklist

- [ ] Can describe actual versus amortised cost
- [ ] identifies scope, period and currency
- [ ] documents source fields and data freshness
- [ ] does not assume all billing accounts have identical schemas.

## Suggested 3.5-hour session

| Activity | Time |
|---|---:|
| Concepts and architecture | 45 min |
| Instructor demonstration | 45 min |
| Guided implementation | 60 min |
| Independent lab and validation | 45 min |
| Review and questions | 15 min |
| **Total** | **3.5 hours** |

**Cloud lab safety:** Use an approved development subscription, least privilege and a budget. Do not commit keys, tokens or customer billing exports. Delete or stop billable lab resources when finished.

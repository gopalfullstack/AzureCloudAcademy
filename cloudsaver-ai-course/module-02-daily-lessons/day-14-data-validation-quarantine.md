# Day 14 – Data Validation and Quarantine

**Module:** 02 – Microsoft Azure Cloud and Data Engineering  
**Programme days:** 14  
**Duration:** 3.5 hours

## Learning objective

Protect downstream analytics from malformed or incomplete billing files.

## Detailed topics

1. Source-to-target mapping
2. required columns
3. schema versioning
4. type coercion
5. date and currency validation
6. null handling
7. duplicate rules
8. negative values and credits
9. malformed CSV
10. quarantine design
11. reason codes
12. quality metrics
13. audit metadata
14. replay and remediation.

## Where to learn

- [Azure Data Factory data quality concepts](https://learn.microsoft.com/en-us/azure/data-factory/concepts-data-flow-schema-drift)
- [Python CSV](https://docs.python.org/3/library/csv.html)
- [Pandas missing data](https://pandas.pydata.org/docs/user_guide/missing_data.html)

## Instructor-led practical lab

Build a validator for synthetic exports. Test missing columns, invalid dates, nonnumeric costs, duplicates and negative adjustments. Write valid rows to curated storage and invalid rows plus reason codes to quarantine.

## Expected deliverables

- [ ] validator.py
- [ ] valid output
- [ ] quarantine output
- [ ] quality summary with counts and reasons.

## Completion checklist

- [ ] Bad records are not silently dropped
- [ ] validation rules are documented
- [ ] quality summary reconciles input = accepted + rejected
- [ ] credits are not automatically discarded.

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

# Day 19 – CloudSaver Data Modelling

**Module:** 03 – FinOps Analytics and Database Engineering  
**Programme day:** 19  
**Duration:** 3.5 hours

## Learning objective

Design a schema that supports traceable billing facts and useful cost dimensions.

## Detailed topics

1. Fact versus dimension tables
2. grain and uniqueness
3. cost fact table
4. subscription/resource/service/resource-group dimensions
5. date dimension
6. tags and ownership metadata
7. currency
8. billing period
9. source file lineage
10. refresh timestamps
11. snapshots
12. credits and adjustments
13. slowly changing attributes concepts
14. ER diagrams.

## Where to learn

- [Microsoft dimensional modelling](https://learn.microsoft.com/en-us/power-bi/guidance/star-schema)
- [PostgreSQL data types](https://www.postgresql.org/docs/current/datatype.html)
- [dbdiagram.io](https://dbdiagram.io/)

## Hands-on practical lab

Design an ER diagram and define the grain of each fact. Map source export fields to model columns. Explain how source file, billing period, currency and adjustment records are retained for auditability.

## Expected deliverables

- [ ] ER diagram
- [ ] data dictionary
- [ ] source-to-target mapping
- [ ] SQL DDL draft.

## Completion checklist

- [ ] Every fact has a defined grain
- [ ] joins have documented keys
- [ ] currency and period are explicit
- [ ] lineage and refresh metadata are preserved.

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

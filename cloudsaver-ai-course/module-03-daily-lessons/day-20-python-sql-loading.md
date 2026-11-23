# Day 20 – Python and SQL Data Loading

**Module:** 03 – FinOps Analytics and Database Engineering  
**Programme day:** 20  
**Duration:** 3.5 hours

## Learning objective

Build a repeatable loader that writes validated billing data into PostgreSQL.

## Detailed topics

1. Python database drivers
2. SQLAlchemy engine and sessions
3. parameterised SQL
4. batch inserts
5. transactions
6. commit and rollback
7. upsert concepts
8. staging tables
9. error handling
10. connection pooling
11. migrations concepts
12. loader logging
13. idempotent load keys.

## Where to learn

- [SQLAlchemy tutorial](https://docs.sqlalchemy.org/en/20/tutorial/)
- [Psycopg documentation](https://www.psycopg.org/psycopg3/docs/)
- [Pandas to_sql](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.to_sql.html)

## Hands-on practical lab

Build a Python loader that reads cleaned CSV data, validates required fields, loads a staging table, then merges accepted records into cost facts. Re-run the same file and verify no duplicate billing facts.

## Expected deliverables

- [ ] Python loader
- [ ] requirements file
- [ ] staging and target tables
- [ ] run log
- [ ] repeat-run test.

## Completion checklist

- [ ] Uses parameterised statements
- [ ] transactions protect partial loads
- [ ] repeated ingestion is idempotent
- [ ] failed rows are reported.

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

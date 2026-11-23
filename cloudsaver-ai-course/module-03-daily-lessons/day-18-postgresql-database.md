# Day 18 – PostgreSQL Database Engineering

**Module:** 03 – FinOps Analytics and Database Engineering  
**Programme day:** 18  
**Duration:** 3.5 hours

## Learning objective

Create and operate a local PostgreSQL database for CloudSaver cost records.

## Detailed topics

1. Install PostgreSQL and a client
2. databases and schemas
3. tables and data types
4. numeric precision for money
5. primary and foreign keys
6. constraints
7. indexes
8. transactions and ACID
9. roles and grants
10. views
11. backup and restore
12. Python connectivity
13. SQLAlchemy introduction
14. connection strings and environment configuration.

## Where to learn

- [PostgreSQL documentation](https://www.postgresql.org/docs/current/)
- [PostgreSQL constraints](https://www.postgresql.org/docs/current/ddl-constraints.html)
- [SQLAlchemy Unified Tutorial](https://docs.sqlalchemy.org/en/20/tutorial/)

## Hands-on practical lab

Create a development database and tables for subscriptions, resources and cost records. Load synthetic records, query them, create a read-only reporting role and test backup/restore.

## Expected deliverables

- [ ] SQL schema
- [ ] seed script
- [ ] connection test
- [ ] backup/restore evidence.

## Completion checklist

- [ ] Uses numeric types appropriate for money
- [ ] keys and constraints are present
- [ ] credentials are outside source control
- [ ] read-only role cannot modify data.

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

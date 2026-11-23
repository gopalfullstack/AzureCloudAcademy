# Day 46 – PostgreSQL and FastAPI Integration

**Module:** 07 – FastAPI, Terraform, DevOps and Application Deployment  
**Programme day:** 46  
**Duration:** 3.5 hours

## Learning objective

Connect the API to the CloudSaver database using safe data-access patterns.

## Detailed topics

1. Database configuration
2. SQLAlchemy engine/session
3. ORM models
4. dependency injection for sessions
5. CRUD patterns
6. parameterised queries
7. transactions
8. pagination
9. filtering
10. connection pooling
11. Alembic migrations
12. test database
13. database exception handling.

## Where to learn

- [SQLAlchemy ORM](https://docs.sqlalchemy.org/en/20/orm/)
- [Alembic tutorial](https://alembic.sqlalchemy.org/en/latest/tutorial.html)
- [FastAPI SQL databases](https://fastapi.tiangolo.com/tutorial/sql-databases/)

## Hands-on practical lab

Connect the API to PostgreSQL. Implement read endpoints for costs and recommendations and CRUD for a synthetic recommendation record. Add migration scripts and test invalid IDs and database failures.

## Expected deliverables

- [ ] Database models
- [ ] migration
- [ ] repository/service layer
- [ ] API endpoints
- [ ] integration tests.

## Completion checklist

- [ ] Uses a session lifecycle correctly
- [ ] migrations reproduce schema
- [ ] queries are parameterised
- [ ] errors do not expose credentials or SQL internals.

## Suggested session timetable

| Activity | Time |
|---|---:|
| Concepts and architecture | 45 min |
| Instructor demonstration | 45 min |
| Guided implementation | 60 min |
| Independent lab and validation | 45 min |
| Review and questions | 15 min |
| **Total** | **3.5 hours** |

**Deployment safety:** Use a dedicated development environment and budget. Apply least privilege, keep secrets in approved secret stores and review Terraform plans before provisioning resources.

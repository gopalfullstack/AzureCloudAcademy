# Day 17 – SQL for Cost Analytics

**Module:** 03 – FinOps Analytics and Database Engineering  
**Programme day:** 17  
**Duration:** 3.5 hours

## Learning objective

Write queries that transform billing records into reliable cost summaries.

## Detailed topics

1. Relational database concepts
2. SELECT and aliases
3. WHERE and date filters
4. ORDER BY and LIMIT
5. aggregate functions
6. GROUP BY and HAVING
7. INNER and LEFT JOIN
8. subqueries
9. common table expressions
10. CASE
11. date functions
12. window functions and ranking
13. null handling
14. query plans and indexes basics.

## Where to learn

- [PostgreSQL tutorial](https://www.postgresql.org/docs/current/tutorial.html)
- [SQLBolt interactive lessons](https://sqlbolt.com/)
- [PostgreSQL window functions](https://www.postgresql.org/docs/current/tutorial-window.html)

## Hands-on practical lab

Using a provided billing table, write queries for daily spend, top services, subscription totals, resource-group totals, month-over-month change and top five resources. Validate at least two queries manually.

## Expected deliverables

- [ ] sql_cost_analysis.sql with comments
- [ ] query result screenshots or exports
- [ ] validation notes.

## Completion checklist

- [ ] Queries return correct scoped totals
- [ ] joins do not multiply cost rows
- [ ] date filters are explicit
- [ ] learner explains GROUP BY and window function use.

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

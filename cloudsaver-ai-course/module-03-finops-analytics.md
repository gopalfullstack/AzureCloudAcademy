# Module 03 – FinOps Analytics and Database Engineering

**Schedule:** Days 16–22  
**Purpose:** Turn curated billing records into trusted cost intelligence.  
**Outcome:** A PostgreSQL cost model, reusable analytics queries and a Power BI dashboard.

## Learning outcomes

Learners understand FinOps practices, relational data modelling, SQL, PostgreSQL, cost allocation and dashboard design.

## Topic-by-topic syllabus

### 3.1 FinOps principles
- FinOps definition and cross-functional operating model
- Inform, Optimise and Operate lifecycle
- Engineering, finance and business responsibilities
- Cost visibility and accountability
- Cost allocation and ownership
- Showback and chargeback
- Budgets, forecasts and variance
- Cost anomaly investigation
- Unit economics and workload cost
- Optimisation versus reliability trade-offs
- FinOps metrics and stakeholder reporting

**Lab:** Review a synthetic monthly cost report and write an investigation summary for a cloud engineering and finance audience.

### 3.2 SQL fundamentals
- Relational database concepts
- Tables, rows, columns and data types
- Primary and foreign keys
- SELECT, WHERE, ORDER BY and LIMIT
- GROUP BY and HAVING
- SUM, AVG, COUNT, MIN and MAX
- INNER, LEFT and other JOINs
- Subqueries and common table expressions
- CASE expressions
- Date and time functions
- Window functions and ranking
- Views and reusable queries
- Query plans and indexing basics

**Lab:** Write queries for daily spend, top services, subscription totals and month-over-month changes.

### 3.3 PostgreSQL
- Installation and connection tools
- Database and schema creation
- Table definitions and constraints
- Numeric precision for financial values
- Indexes and query performance
- Views and materialised views
- Transactions and ACID basics
- Roles and permissions
- Backup and restore
- Python database connectivity
- SQLAlchemy fundamentals
- Connection pooling and migrations concepts

**Lab:** Create a PostgreSQL database and load curated synthetic cost records.

### 3.4 CloudSaver data model
- Fact and dimension modelling
- Cost fact grain and uniqueness
- Subscription and resource dimensions
- Service and resource-group dimensions
- Date dimension
- Tag and ownership metadata
- Currency and billing-period handling
- Historical snapshots
- Source lineage and refresh timestamps
- Handling credits and adjustments

Suggested entities:
- subscriptions
- resources
- services
- cost_records
- daily_cost_summary
- anomalies
- forecasts
- recommendations
- approvals

**Lab:** Design an ER diagram, define table keys and document the grain of each fact table.

### 3.5 Cost analytics and allocation
- Daily, weekly and monthly aggregation
- Subscription and service breakdowns
- Resource-group analysis
- Tag-based allocation
- Missing owner and environment tags
- Budget versus actual
- Variance and percentage change
- Top cost contributors
- Trend and period comparison
- Cost per workload where attribution data supports it
- Data completeness indicators

**Lab:** Implement reusable SQL views and Python reports. Reconcile totals to the source export.

### 3.6 Power BI
- Power BI Desktop and data connectors
- PostgreSQL connection
- Power Query transformations
- Relationships and star schema
- DAX measures and calculated columns
- KPI cards and trend charts
- Bar charts, matrix and tables
- Slicers and filters
- Drill-through and tooltips
- Refresh configuration
- Dashboard usability and accessibility

**Lab:** Create a CloudSaver dashboard with spend trend, subscription/service breakdown, top contributors and budget variance.

## Seven-day practical sequence

| Day | Focus | Evidence |
|---|---|---|
| 16 | FinOps concepts | Cost investigation notes |
| 17 | SQL | Cost analysis query set |
| 18 | PostgreSQL | Database and tables |
| 19 | Data modelling | ER diagram and schema |
| 20 | Python + SQL | Automated data load |
| 21 | Cost allocation | Aggregation reports |
| 22 | Power BI | Interactive dashboard |

## Final assignment – CloudSaver Cost Intelligence Dashboard

Deliver:
1. PostgreSQL schema and ER diagram.
2. Repeatable synthetic data-loading script.
3. SQL queries for daily and monthly spend.
4. Subscription, service and resource-group analysis.
5. Budget-versus-actual report.
6. Missing-tag and ownership indicators.
7. Power BI dashboard.
8. Reconciliation notes explaining exclusions and adjustments.

**Acceptance criteria:** Dashboard totals reconcile to the selected source data and clearly display currency, period, freshness and any known limitations.

# Module 07 – FastAPI, Terraform, DevOps and Application Deployment

**Schedule:** Days 45–52  
**Purpose:** Package CloudSaver components behind secure APIs and deploy repeatable infrastructure.  
**Outcome:** A deployable backend with automated CI/CD and infrastructure as code.

## Learning outcomes

Learners can build FastAPI services, integrate PostgreSQL, protect APIs, provision Azure infrastructure with Terraform and automate build/test/deployment workflows.

## Topic-by-topic syllabus

### 7.1 FastAPI backend
- Backend architecture and API design
- FastAPI application structure
- Routers and endpoint organisation
- GET, POST, PUT, PATCH and DELETE
- Path and query parameters
- Request and response bodies
- Pydantic models and validation
- Status codes and error responses
- Dependency injection
- Middleware and CORS concepts
- Async programming overview
- OpenAPI and Swagger UI
- Logging and exception handling

**Lab:** Build cost, AKS, anomaly, forecast and recommendation endpoints.

Suggested routes:
```text
GET  /api/costs
GET  /api/costs/daily
GET  /api/costs/services
GET  /api/aks/nodes
GET  /api/aks/workloads
GET  /api/anomalies
GET  /api/forecasts
GET  /api/recommendations
POST /api/copilot/query
POST /api/recommendations/{id}/approve
POST /api/recommendations/{id}/reject
```

### 7.2 PostgreSQL integration
- Database connection configuration
- SQLAlchemy models and sessions
- Connection pooling
- CRUD patterns
- Transactions
- Pagination and filtering
- Query parameter validation
- Database migrations with Alembic
- Error handling
- Test database strategy

**Lab:** Connect FastAPI to PostgreSQL and implement cost and recommendation CRUD operations.

### 7.3 Authentication and authorisation
- Authentication versus authorisation
- OAuth 2.0 and OpenID Connect concepts
- Microsoft Entra ID application registration
- Access tokens and JWT validation
- API scopes and roles
- Role-based access control
- Finance, engineer, approver and administrator roles
- Permission checks on every relevant endpoint
- Tenant/scope filtering

**Lab:** Protect selected endpoints and test allowed and denied access for different roles.

### 7.4 Terraform and IaC
- IaC principles and Terraform workflow
- Providers and resource blocks
- Variables, locals and outputs
- Data sources
- Dependencies
- Modules and reusable configuration
- State files and remote state
- State locking concepts
- Workspaces and environment separation
- terraform init, fmt, validate, plan and apply
- Import and drift concepts
- Resource tags and naming
- Safe destroy and cleanup

**Lab:** Provision a small development environment using Terraform. Review the plan before applying.

### 7.5 Azure DevOps and CI/CD
- CI/CD concepts
- Azure DevOps projects and repositories
- YAML pipeline structure
- Triggers and stages
- Build and test jobs
- Dependencies and artifacts
- Pipeline variables and variable groups
- Secure service connections
- Deployment environments
- Approval checks
- Release strategies
- Pipeline logs and troubleshooting

**Lab:** Build a pipeline that installs dependencies, runs tests, builds an image and publishes an artifact/image.

### 7.6 Docker and registry workflow
- Production-oriented Dockerfiles
- Multi-stage builds
- Non-root container users
- Image tagging and versioning
- Azure Container Registry
- Image push and pull
- Vulnerability scanning concepts
- Runtime environment configuration
- Health checks and logs

**Lab:** Build and publish a versioned CloudSaver API image to ACR.

### 7.7 Hosting and deployment
- Azure App Service concepts
- Azure Container Apps concepts
- Choosing a hosting model for an MVP
- Environment variables and configuration
- Managed identity
- Networking and TLS
- Health probes
- Scaling and deployment slots
- Application logging
- Cost and operational trade-offs
- When AKS is justified and when it is not

**Lab:** Deploy the API to a simple development hosting target and verify health and connectivity.

### 7.8 Monitoring and operations
- Azure Monitor concepts
- Application Insights
- Structured application logs
- Request and dependency telemetry
- Error rates and latency
- Availability checks
- Alerts and dashboards
- Log retention
- Azure budgets and cost alerts

**Lab:** Add telemetry and create a basic operational dashboard.

## Eight-day practical sequence

| Day | Focus | Evidence |
|---|---|---|
| 45 | FastAPI | API endpoints and Swagger |
| 46 | PostgreSQL integration | Database-backed API |
| 47 | Entra ID and RBAC | Protected endpoints |
| 48 | Terraform | Repeatable infrastructure |
| 49 | Azure DevOps | Build/test pipeline |
| 50 | Docker and ACR | Published image |
| 51 | Deployment and identity | Running development API |
| 52 | Monitoring | Logs, metrics and alerts |

## Final assignment – CloudSaver Backend and Deployment

Deliver:
1. FastAPI source code and OpenAPI documentation.
2. PostgreSQL integration and migrations.
3. Authentication and role-based authorisation.
4. Terraform configuration.
5. CI pipeline with automated tests.
6. Versioned container image.
7. Development deployment guide.
8. Monitoring and budget controls.

**Acceptance criteria:** A clean deployment can be reproduced from documented steps, tests run in the pipeline, secrets are not stored in source control and access is checked server-side.

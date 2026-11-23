# Day 45 – FastAPI Foundations and API Design

**Module:** 07 – FastAPI, Terraform, DevOps and Application Deployment  
**Programme day:** 45  
**Duration:** 3.5 hours

## Learning objective

Build a well-structured REST API for CloudSaver capabilities.

## Detailed topics

1. Backend/API architecture
2. REST resource design
3. FastAPI app structure
4. routers
5. GET/POST/PUT/PATCH/DELETE
6. path/query parameters
7. request/response bodies
8. Pydantic models
9. validation
10. status codes
11. error responses
12. dependency injection
13. middleware
14. CORS
15. async overview
16. OpenAPI/Swagger
17. logging.

## Where to learn

- [FastAPI tutorial](https://fastapi.tiangolo.com/tutorial/)
- [Pydantic docs](https://docs.pydantic.dev/latest/)
- [HTTP methods](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods)

## Hands-on practical lab

Create a FastAPI service with endpoints for costs, daily costs, services, AKS nodes/workloads, anomalies, forecasts and recommendations. Add Pydantic request/response models, filtering and pagination, then inspect Swagger UI.

## Expected deliverables

- [ ] FastAPI project
- [ ] routers
- [ ] Pydantic schemas
- [ ] API test collection
- [ ] OpenAPI screenshot.

## Completion checklist

- [ ] Endpoints use correct methods/status codes
- [ ] request validation works
- [ ] errors are consistent
- [ ] API docs are generated
- [ ] no business logic is embedded in route handlers.

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

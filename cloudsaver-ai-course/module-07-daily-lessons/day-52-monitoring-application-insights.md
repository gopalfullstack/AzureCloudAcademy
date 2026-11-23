# Day 52 – Monitoring and Application Insights

**Module:** 07 – FastAPI, Terraform, DevOps and Application Deployment  
**Programme day:** 52  
**Duration:** 3.5 hours

## Learning objective

Instrument the CloudSaver API and diagnose basic operational issues.

## Detailed topics

1. Azure Monitor
2. Application Insights
3. structured logs
4. request/dependency telemetry
5. traces and correlation IDs
6. latency
7. error rates
8. availability tests
9. custom metrics
10. dashboards
11. alert rules
12. retention
13. sampling
14. privacy in telemetry
15. cost controls.

## Where to learn

- [Application Insights overview](https://learn.microsoft.com/en-us/azure/azure-monitor/app/app-insights-overview)
- [OpenTelemetry for Azure Monitor](https://learn.microsoft.com/en-us/azure/azure-monitor/app/opentelemetry-enable)
- [Azure Monitor alerts](https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/alerts-overview)

## Hands-on practical lab

Instrument API requests and dependencies, generate normal and failing requests, inspect correlated traces and create a basic dashboard/alert for error rate or latency. Avoid logging tokens or sensitive billing rows.

## Expected deliverables

- [ ] Telemetry configuration
- [ ] dashboard
- [ ] sample trace
- [ ] alert definition
- [ ] operational runbook.

## Completion checklist

- [ ] Can trace request to dependency
- [ ] errors and latency are visible
- [ ] telemetry avoids secrets/sensitive payloads
- [ ] alert threshold and retention are documented.

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

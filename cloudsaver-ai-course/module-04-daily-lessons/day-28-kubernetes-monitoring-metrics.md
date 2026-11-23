# Day 28 – Kubernetes Monitoring and Metrics

**Module:** 04 – Docker, Kubernetes, AKS and Container FinOps  
**Programme day:** 28  
**Duration:** 3.5 hours

## Learning objective

Collect and interpret node, pod and container health/utilisation signals.

## Detailed topics

1. Metrics Server
2. Azure Monitor for containers/Container Insights
3. Prometheus and Grafana concepts
4. node CPU/memory
5. pod/container metrics
6. restarts and pending pods
7. disk and network observations
8. metrics scrape intervals
9. retention
10. dashboards
11. alert thresholds
12. telemetry limitations.

## Where to learn

- [Azure Monitor for AKS](https://learn.microsoft.com/en-us/azure/azure-monitor/containers/container-insights-overview)
- [Metrics Server](https://github.com/kubernetes-sigs/metrics-server)
- [Prometheus](https://prometheus.io/docs/introduction/overview/)
- [Grafana](https://grafana.com/docs/)

## Hands-on practical lab

Collect or use a supplied metrics dataset. Create a dashboard view for node capacity, pod requests, observed utilisation, restarts and pending pods. Identify gaps in metric coverage and freshness.

## Expected deliverables

- [ ] Metrics dataset
- [ ] dashboard or screenshots
- [ ] alert definitions
- [ ] metrics freshness notes.

## Completion checklist

- [ ] Labels metrics with cluster and time window
- [ ] distinguishes usage from requests
- [ ] calls out missing/stale metrics
- [ ] avoids inferring billing directly from CPU.

## Suggested session timetable

| Activity | Time |
|---|---:|
| Concepts and architecture | 45 min |
| Instructor demonstration | 45 min |
| Guided implementation | 60 min |
| Independent lab and validation | 45 min |
| Review and questions | 15 min |
| **Total** | **3.5 hours** |

**Cost and safety note:** Use a small, budgeted development cluster or local Kubernetes where possible. Record the time window and source for every cost input. Clearly distinguish actual billed node infrastructure costs from estimated namespace/workload allocations. Never describe a CPU percentage as an Azure invoice amount.

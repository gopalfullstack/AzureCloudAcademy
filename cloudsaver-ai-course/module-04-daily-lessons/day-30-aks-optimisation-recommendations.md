# Day 30 – AKS Optimisation Recommendations

**Module:** 04 – Docker, Kubernetes, AKS and Container FinOps  
**Programme day:** 30  
**Duration:** 3.5 hours

## Learning objective

Turn resource and cost evidence into safe, ranked optimisation candidates.

## Detailed topics

1. CPU/memory right-sizing
2. excessive requests and limits
3. node-pool sizing
4. workload consolidation
5. bin packing
6. autoscaling review
7. idle capacity
8. non-production schedules
9. Spot VM trade-offs
10. storage/network review
11. availability and performance safeguards
12. recommendation confidence
13. savings estimation assumptions
14. approval requirements.

## Where to learn

- [AKS best practices](https://learn.microsoft.com/en-us/azure/aks/best-practices)
- [Cluster autoscaler](https://learn.microsoft.com/en-us/azure/aks/cluster-autoscaler)
- [Spot node pools](https://learn.microsoft.com/en-us/azure/aks/spot-node-pool)

## Hands-on practical lab

Build a rule-based recommendation engine from the supplied metrics and cost pool. Each recommendation must include affected scope, evidence, estimated impact, confidence, operational risk and validation step. Do not execute changes.

## Expected deliverables

- [ ] Recommendation engine
- [ ] ranked report
- [ ] evidence/risk fields
- [ ] test cases
- [ ] final AKS Cost Intelligence demo.

## Completion checklist

- [ ] Every recommendation is traceable
- [ ] estimated savings are labelled
- [ ] reliability risks are stated
- [ ] no production changes are executed automatically.

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

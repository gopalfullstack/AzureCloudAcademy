# Day 29 – Kubernetes Cost Allocation

**Module:** 04 – Docker, Kubernetes, AKS and Container FinOps  
**Programme day:** 29  
**Duration:** 3.5 hours

## Learning objective

Build a transparent method to attribute node infrastructure cost to namespaces and workloads.

## Detailed topics

1. Actual node infrastructure expenditure
2. node pool cost mapping
3. workload inventory
4. namespace labels
5. requests versus usage allocation
6. shared/system workload treatment
7. idle/unallocated capacity
8. PVC/storage cost
9. network costs
10. time-window alignment
11. allocation formula
12. estimated versus billed cost
13. double-counting risks.

## Where to learn

- [OpenCost documentation](https://opencost.io/docs/)
- [Kubecost concepts](https://docs.kubecost.com/)
- [FinOps allocation](https://www.finops.org/framework/capabilities/allocation/)

## Hands-on practical lab

Use synthetic node-pool cost and pod metrics. Implement at least one allocation method (for example CPU/memory requests or measured usage), define treatment of system workloads and idle capacity, and reconcile allocations to the input infrastructure cost pool.

## Expected deliverables

- [ ] Allocation script/notebook
- [ ] formula and assumptions
- [ ] namespace/workload allocation report
- [ ] reconciliation evidence.

## Completion checklist

- [ ] Allocated totals reconcile to chosen cost pool
- [ ] measured billed costs are separated from estimates
- [ ] time windows align
- [ ] shared/idle cost treatment is explicit.

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

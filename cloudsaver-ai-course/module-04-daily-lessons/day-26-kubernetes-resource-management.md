# Day 26 – Kubernetes Resource Management

**Module:** 04 – Docker, Kubernetes, AKS and Container FinOps  
**Programme day:** 26  
**Duration:** 3.5 hours

## Learning objective

Measure resource requests, limits and scheduling efficiency.

## Detailed topics

1. CPU and memory requests/limits
2. actual usage versus requests
3. node capacity and allocatable
4. scheduler placement
5. taints/tolerations
6. affinity/anti-affinity
7. ResourceQuota and LimitRange
8. HPA/VPA concepts
9. Cluster Autoscaler
10. bin packing
11. fragmentation
12. over/under-provisioning
13. QoS classes
14. eviction.

## Where to learn

- [Resource management](https://kubernetes.io/docs/concepts/configuration/manage-resources-containers/)
- [Assign Pods to Nodes](https://kubernetes.io/docs/concepts/scheduling-eviction/assign-pod-node/)
- [HPA](https://kubernetes.io/docs/tasks/run-application/horizontal-pod-autoscale/)

## Hands-on practical lab

Deploy workloads with different CPU/memory requests and limits. Inspect scheduling, capacity and observed metrics. Create a namespace quota and explain why a request that is too high can waste schedulable capacity.

## Expected deliverables

- [ ] Workload manifests
- [ ] capacity/request comparison
- [ ] quota configuration
- [ ] resource utilisation notes.

## Completion checklist

- [ ] Distinguishes requested, limited and observed resources
- [ ] explains scheduling outcomes
- [ ] proposes sizing changes with performance safeguards.

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

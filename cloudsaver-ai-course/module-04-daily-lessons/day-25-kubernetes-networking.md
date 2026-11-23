# Day 25 – Kubernetes Networking

**Module:** 04 – Docker, Kubernetes, AKS and Container FinOps  
**Programme day:** 25  
**Duration:** 3.5 hours

## Learning objective

Understand how pods, services and external clients communicate in a cluster.

## Detailed topics

1. Pod network model
2. pod-to-pod communication
3. Service virtual IP
4. ClusterIP, NodePort and LoadBalancer
5. CoreDNS and service discovery
6. ingress and ingress controllers
7. CNI concepts
8. NetworkPolicy
9. namespaces and network segmentation
10. DNS and connectivity troubleshooting.

## Where to learn

- [Kubernetes Services](https://kubernetes.io/docs/concepts/services-networking/service/)
- [DNS for Services and Pods](https://kubernetes.io/docs/concepts/services-networking/dns-pod-service/)
- [Network Policies](https://kubernetes.io/docs/concepts/services-networking/network-policies/)
- [Ingress](https://kubernetes.io/docs/concepts/services-networking/ingress/)

## Hands-on practical lab

Deploy frontend, backend and database workloads in separate namespaces or labelled tiers. Verify service DNS and connectivity, then apply a NetworkPolicy to restrict database access to the backend.

## Expected deliverables

- [ ] Three-tier manifests
- [ ] connectivity test results
- [ ] NetworkPolicy YAML
- [ ] network flow diagram.

## Completion checklist

- [ ] Can explain Service discovery
- [ ] tests DNS and connectivity
- [ ] policy blocks unauthorised paths without breaking required traffic.

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

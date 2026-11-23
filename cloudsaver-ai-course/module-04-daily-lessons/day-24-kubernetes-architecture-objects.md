# Day 24 – Kubernetes Architecture and Objects

**Module:** 04 – Docker, Kubernetes, AKS and Container FinOps  
**Programme day:** 24  
**Duration:** 3.5 hours

## Learning objective

Deploy a containerised application to a local Kubernetes cluster.

## Detailed topics

1. Control plane: API Server, Scheduler, Controller Manager and etcd
2. worker node components: kubelet, kube-proxy and runtime
3. Pods
4. ReplicaSets
5. Deployments
6. rollout and rollback
7. Namespaces
8. labels/selectors
9. Services
10. ConfigMaps
11. Secrets
12. volumes
13. YAML manifests
14. kubectl.

## Where to learn

- [Kubernetes concepts](https://kubernetes.io/docs/concepts/)
- [Learn Kubernetes basics](https://kubernetes.io/docs/tutorials/kubernetes-basics/)
- [kind](https://kind.sigs.k8s.io/)

## Hands-on practical lab

Create a local kind or Minikube cluster. Deploy a multi-replica Python service, expose it with a ClusterIP Service, inspect pods and events, then update the image and perform a rollout/rollback.

## Expected deliverables

- [ ] Deployment and Service YAML
- [ ] kubectl command notes
- [ ] rollout evidence.

## Completion checklist

- [ ] Can explain control plane versus worker node
- [ ] manifests are declarative
- [ ] readiness and replicas are checked
- [ ] rollout can be reversed.

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

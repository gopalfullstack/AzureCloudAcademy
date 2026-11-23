# Day 27 – Azure Kubernetes Service and Node Pools

**Module:** 04 – Docker, Kubernetes, AKS and Container FinOps  
**Programme day:** 27  
**Duration:** 3.5 hours

## Learning objective

Understand AKS architecture, node pools and the Azure resources that contribute to cluster cost.

## Detailed topics

1. AKS managed control plane
2. cluster and node-pool concepts
3. system versus user pools
4. VM SKU and disk choices
5. zones
6. network modes and Azure CNI concepts
7. ACR integration
8. Entra ID and managed identity
9. kubectl access
10. scaling
11. upgrades
12. maintenance
13. monitoring
14. AKS cost dimensions.

## Where to learn

- [AKS overview](https://learn.microsoft.com/en-us/azure/aks/what-is-aks)
- [Node pools](https://learn.microsoft.com/en-us/azure/aks/create-node-pools)
- [AKS pricing](https://azure.microsoft.com/en-us/pricing/details/kubernetes-service/)
- [AKS identity](https://learn.microsoft.com/en-us/azure/aks/managed-identity-overview)

## Hands-on practical lab

Inspect an existing training cluster or create a small development cluster only after checking budget and permissions. Inventory node pools, VM sizes, zones, disk and scaling configuration; deploy a sample image from ACR and scale a deployment.

## Expected deliverables

- [ ] AKS architecture diagram
- [ ] node-pool inventory
- [ ] SKU/cost notes
- [ ] deployment evidence
- [ ] cleanup confirmation.

## Completion checklist

- [ ] Can distinguish control-plane and worker-node costs
- [ ] explains system/user pools
- [ ] identifies billable underlying resources
- [ ] cleans up lab resources.

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

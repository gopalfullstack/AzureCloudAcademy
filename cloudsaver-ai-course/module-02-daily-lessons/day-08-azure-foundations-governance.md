# Day 8 – Azure Foundations and Governance

**Module:** 02 – Microsoft Azure Cloud and Data Engineering  
**Programme days:** 08  
**Duration:** 3.5 hours

## Learning objective

Understand Azure's resource hierarchy and establish a controlled development environment.

## Detailed topics

1. Azure global infrastructure
2. regions and availability zones
3. management groups, subscriptions and resource groups
4. Azure Resource Manager and resource providers
5. Portal, Cloud Shell and Azure CLI
6. naming/tagging standards
7. RBAC scope and built-in roles
8. budgets and alerts
9. Pricing Calculator
10. environment separation.

## Where to learn

- [Azure fundamentals](https://learn.microsoft.com/en-us/training/paths/azure-fundamentals-describe-azure-architecture-services/)
- [Azure CLI](https://learn.microsoft.com/en-us/cli/azure/)
- [Azure RBAC](https://learn.microsoft.com/en-us/azure/role-based-access-control/overview)
- [Budgets](https://learn.microsoft.com/en-us/azure/cost-management-billing/costs/tutorial-acm-create-budgets)

## Instructor-led practical lab

Create a dedicated resource group with consistent name, owner, environment and project tags. Inspect subscription/resource-group scopes, assign only required permissions, create a small budget and alert, and estimate the lab cost before deploying anything.

## Expected deliverables

- [ ] A documented environment inventory
- [ ] Azure CLI commands
- [ ] resource-group tags
- [ ] budget/alert evidence
- [ ] cleanup plan.

## Completion checklist

- [ ] Can explain subscription versus resource group
- [ ] can inspect resources with CLI
- [ ] can explain RBAC scope
- [ ] budget and tags are configured
- [ ] no unnecessary resources are left running.

## Suggested 3.5-hour session

| Activity | Time |
|---|---:|
| Concepts and architecture | 45 min |
| Instructor demonstration | 45 min |
| Guided implementation | 60 min |
| Independent lab and validation | 45 min |
| Review and questions | 15 min |
| **Total** | **3.5 hours** |

**Cloud lab safety:** Use an approved development subscription, least privilege and a budget. Do not commit keys, tokens or customer billing exports. Delete or stop billable lab resources when finished.

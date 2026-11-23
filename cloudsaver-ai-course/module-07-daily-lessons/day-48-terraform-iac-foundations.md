# Day 48 – Terraform and Infrastructure as Code

**Module:** 07 – FastAPI, Terraform, DevOps and Application Deployment  
**Programme day:** 48  
**Duration:** 3.5 hours

## Learning objective

Provision a small Azure development environment using repeatable Terraform configuration.

## Detailed topics

1. IaC concepts
2. Terraform providers
3. resources/data sources
4. variables, locals and outputs
5. dependency graph
6. modules
7. state
8. remote backend and locking
9. workspaces/environment separation
10. init/fmt/validate/plan/apply
11. drift/import concepts
12. naming/tags
13. sensitive variables
14. destroy and cleanup.

## Where to learn

- [Terraform AzureRM provider](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs)
- [Terraform Azure tutorial](https://developer.hashicorp.com/terraform/tutorials/azure-get-started)
- [Terraform state](https://developer.hashicorp.com/terraform/language/state)

## Hands-on practical lab

Write Terraform for a small development resource group and one low-cost supporting resource. Run fmt, validate and plan; review the plan before apply; document state handling and destroy resources after lab.

## Expected deliverables

- [ ] Terraform files
- [ ] variables example
- [ ] plan output
- [ ] deployment/cleanup notes
- [ ] module diagram.

## Completion checklist

- [ ] Plan is reviewed before apply
- [ ] secrets are not stored in code
- [ ] state is treated as sensitive
- [ ] resources are tagged and cleaned up.

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

# Day 51 – Deploying the CloudSaver API on Azure

**Module:** 07 – FastAPI, Terraform, DevOps and Application Deployment  
**Programme day:** 51  
**Duration:** 3.5 hours

## Learning objective

Deploy the backend to an appropriate development hosting target.

## Detailed topics

1. App Service and Container Apps concepts
2. choosing hosting model
3. environment variables
4. managed identity
5. secrets and Key Vault
6. TLS
7. networking
8. health probes
9. scaling
10. deployment revisions/slots
11. database connectivity
12. cost trade-offs
13. when AKS is and is not justified.

## Where to learn

- [Azure Container Apps](https://learn.microsoft.com/en-us/azure/container-apps/overview)
- [App Service containers](https://learn.microsoft.com/en-us/azure/app-service/configure-custom-container)
- [Managed identities](https://learn.microsoft.com/en-us/entra/identity/managed-identities-azure-resources/overview)

## Hands-on practical lab

Deploy the API container to a simple development hosting target such as Container Apps or App Service. Configure health checks and identity-based access to required dependencies. Verify API docs and clean up if the environment is temporary.

## Expected deliverables

- [ ] Deployment guide
- [ ] running endpoint
- [ ] health check evidence
- [ ] environment configuration without secrets
- [ ] cost/cleanup notes.

## Completion checklist

- [ ] Deployment is repeatable
- [ ] secrets are not embedded
- [ ] identity has minimum permissions
- [ ] health and connectivity are tested
- [ ] cost is understood.

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

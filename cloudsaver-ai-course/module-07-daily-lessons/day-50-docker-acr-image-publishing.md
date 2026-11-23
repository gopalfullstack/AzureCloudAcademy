# Day 50 – Docker and Azure Container Registry

**Module:** 07 – FastAPI, Terraform, DevOps and Application Deployment  
**Programme day:** 50  
**Duration:** 3.5 hours

## Learning objective

Build and publish a versioned CloudSaver API container image.

## Detailed topics

1. Production Dockerfile
2. multi-stage build
3. minimal base image
4. non-root user
5. dependency pinning
6. .dockerignore
7. environment configuration
8. health checks
9. image tags
10. ACR registry
11. authentication
12. push/pull
13. vulnerability scanning concepts
14. image provenance.

## Where to learn

- [ACR overview](https://learn.microsoft.com/en-us/azure/container-registry/container-registry-intro)
- [Push image to ACR](https://learn.microsoft.com/en-us/azure/container-registry/container-registry-get-started-docker-cli)
- [Docker build best practices](https://docs.docker.com/build/building/best-practices/)

## Hands-on practical lab

Create a multi-stage Dockerfile for FastAPI. Build locally, run as non-root, test health endpoint, tag with a version and publish to an approved ACR using identity-based authentication where available.

## Expected deliverables

- [ ] Dockerfile
- [ ] image tag
- [ ] ACR repository entry
- [ ] scan/test notes
- [ ] build instructions.

## Completion checklist

- [ ] Image runs as non-root
- [ ] secrets are not in layers
- [ ] tags are immutable/versioned
- [ ] image can be pulled and run.

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

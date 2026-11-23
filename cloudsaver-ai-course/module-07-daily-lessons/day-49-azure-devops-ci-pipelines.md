# Day 49 – Azure DevOps CI and YAML Pipelines

**Module:** 07 – FastAPI, Terraform, DevOps and Application Deployment  
**Programme day:** 49  
**Duration:** 3.5 hours

## Learning objective

Automate linting, tests and build validation for CloudSaver.

## Detailed topics

1. CI/CD concepts
2. Azure DevOps project/repository
3. YAML pipeline structure
4. triggers
5. stages/jobs/steps
6. agent pools
7. variables
8. secure variable groups
9. service connections
10. dependencies
11. artifacts
12. test publishing
13. approvals/environments
14. pipeline logs and troubleshooting.

## Where to learn

- [Azure Pipelines documentation](https://learn.microsoft.com/en-us/azure/devops/pipelines/)
- [Python pipeline example](https://learn.microsoft.com/en-us/azure/devops/pipelines/ecosystems/python)
- [YAML schema](https://learn.microsoft.com/en-us/azure/devops/pipelines/yaml-schema/)

## Hands-on practical lab

Create a pipeline that installs dependencies, runs lint and unit tests, builds the API package or container and publishes a build artifact. Keep deployment credentials out of YAML.

## Expected deliverables

- [ ] azure-pipelines.yml
- [ ] successful run
- [ ] test report
- [ ] artifact
- [ ] pipeline README.

## Completion checklist

- [ ] Pipeline runs on a code change
- [ ] failed tests fail the build
- [ ] secrets are stored securely
- [ ] artifacts are versioned.

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

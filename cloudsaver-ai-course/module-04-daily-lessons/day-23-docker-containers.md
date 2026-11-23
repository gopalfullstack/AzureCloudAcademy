# Day 23 – Docker and Container Fundamentals

**Module:** 04 – Docker, Kubernetes, AKS and Container FinOps  
**Programme day:** 23  
**Duration:** 3.5 hours

## Learning objective

Containerise the CloudSaver Python service and understand how its runtime is packaged.

## Detailed topics

1. Containers versus VMs
2. Docker Engine and images
3. layers and registries
4. Docker CLI
5. Dockerfile and build context
6. base images
7. ports and environment variables
8. volumes
9. bridge networks
10. Docker Compose
11. multi-stage builds
12. image tagging
13. CPU/memory limits
14. image hygiene.

## Where to learn

- [Docker getting started](https://docs.docker.com/get-started/)
- [Dockerfile reference](https://docs.docker.com/reference/dockerfile/)
- [Docker Compose](https://docs.docker.com/compose/)

## Hands-on practical lab

Write a Dockerfile for a small Python billing API, build and run it, mount a local reports directory, pass configuration through environment variables and run PostgreSQL beside it using Compose.

## Expected deliverables

- [ ] Dockerfile
- [ ] .dockerignore
- [ ] compose.yaml
- [ ] image build/run commands
- [ ] README.

## Completion checklist

- [ ] Container starts reliably
- [ ] configuration is not baked into image
- [ ] persistent data uses volumes
- [ ] image is tagged and reproducible.

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

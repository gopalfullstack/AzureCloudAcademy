# Module 04 – Docker, Kubernetes, AKS and Container FinOps

**Schedule:** Days 23–30  
**Purpose:** Develop container-platform knowledge and a workload cost-intelligence capability.  
**Outcome:** An AKS/Kubernetes analysis prototype for nodes, namespaces, workloads and resource utilisation.

## Learning outcomes

Learners can containerise an application, deploy it to Kubernetes, understand AKS architecture, inspect resource usage and explain the limitations of Kubernetes cost allocation.

## Topic-by-topic syllabus

### 4.1 Docker and containers
- Containers versus virtual machines
- Docker architecture and Docker Engine
- Images, layers and registries
- Docker CLI and lifecycle
- Dockerfiles and build context
- Base images and image tagging
- Ports, environment variables and volumes
- Networks and container-to-container communication
- Docker Compose
- Multi-stage builds
- Image size and vulnerability basics
- Container CPU and memory limits

**Labs:** Containerise a Python billing processor; run PostgreSQL; connect both services; compose the stack with Docker Compose.

### 4.2 Kubernetes architecture and objects
- Cluster, control plane and worker nodes
- API Server, Scheduler, Controller Manager and etcd
- Kubelet, kube-proxy and container runtime
- Pods and ReplicaSets
- Deployments and rollout history
- StatefulSets and DaemonSets
- Namespaces and labels
- Services: ClusterIP, NodePort and LoadBalancer
- ConfigMaps and Secrets
- Persistent Volumes and Claims
- kubectl commands and YAML manifests

**Lab:** Use kind or Minikube to deploy a multi-replica Python application and expose it through a Service.

### 4.3 Kubernetes networking
- Pod and node networking concepts
- Pod-to-pod communication
- Service discovery and CoreDNS
- ClusterIP and external traffic
- Ingress and ingress controllers
- CNI fundamentals
- NetworkPolicy
- DNS and connectivity troubleshooting
- Network observability concepts

**Lab:** Deploy frontend, backend and database workloads. Test DNS, service discovery and network restrictions.

### 4.4 Kubernetes resource management
- CPU and memory requests
- CPU and memory limits
- Actual usage versus requests and limits
- Node capacity and allocatable resources
- Scheduling and placement
- Taints and tolerations
- Node and pod affinity
- ResourceQuota and LimitRange
- Horizontal Pod Autoscaler
- Vertical Pod Autoscaler concepts
- Cluster Autoscaler
- Bin packing and fragmentation
- Over-provisioning and underutilisation

**Lab:** Deploy workloads with varied requests and limits; inspect scheduling and compare requested resources with observed metrics.

### 4.5 Azure Kubernetes Service
- AKS managed control plane concepts
- Cluster and node-pool architecture
- System and user node pools
- VM SKU selection
- Availability zones
- Networking options and Azure CNI concepts
- Azure Container Registry integration
- Entra ID and managed identity
- kubectl credentials and access
- Node-pool scaling
- Cluster upgrades and maintenance
- Monitoring and operational considerations
- AKS pricing dimensions and cost controls

**Lab:** Create a small development AKS cluster, deploy an image from ACR, inspect node pools and scale a deployment. Delete lab resources after completion.

### 4.6 Monitoring and observability
- Metrics Server
- Azure Monitor for containers / Container Insights
- Prometheus and Grafana concepts
- Node CPU and memory metrics
- Pod and container metrics
- Restarts and failed pods
- Network and storage observations
- Dashboards and alerting
- Metrics freshness and retention

**Lab:** Build a dashboard for node capacity, pod requests, observed utilisation and workload health.

### 4.7 Kubernetes FinOps and allocation
- Infrastructure cost versus workload cost
- Node-level infrastructure expenditure
- Node-pool cost comparisons
- Namespace and workload allocation
- Pod-level attribution limitations
- CPU requested versus used
- Memory requested versus used
- Idle and unallocated capacity
- Shared system workload costs
- Persistent volume and storage costs
- Network cost considerations
- Allocation by team, application and environment
- Allocation methods: requests, usage, equal split and hybrid
- Explain assumptions and avoid double-counting

**Lab:** Use a synthetic node-cost and workload-metrics dataset to calculate an explicitly documented allocation model.

### 4.8 Optimisation recommendations
- CPU and memory right-sizing
- Excessive requests and limits
- Node-pool sizing
- Workload consolidation
- Bin packing opportunities
- Autoscaling review
- Idle capacity investigation
- Scheduling and environment shutdown opportunities
- Spot VM trade-offs
- Storage and network investigation
- Reliability, performance and availability safeguards

**Lab:** Build a rule-based recommendation engine that identifies candidate improvements and explains risk and evidence.

## Eight-day practical sequence

| Day | Focus | Evidence |
|---|---|---|
| 23 | Docker | Containerised Python service |
| 24 | Kubernetes objects | Local cluster deployment |
| 25 | Networking | Three-tier connectivity |
| 26 | Resource management | Requests/limits report |
| 27 | AKS architecture | AKS cluster and node-pool inventory |
| 28 | Metrics and monitoring | Utilisation dataset/dashboard |
| 29 | Cost allocation | Namespace/workload allocation model |
| 30 | Optimisation | AKS cost intelligence report |

## Final assignment – Kubernetes Cost Intelligence

Build a prototype that:
1. Ingests cluster, node-pool and workload inventory.
2. Collects or loads node and pod metrics.
3. Associates infrastructure cost inputs with node pools.
4. Allocates costs using a documented method.
5. Shows namespace and workload estimates.
6. Identifies idle or over-requested capacity.
7. Produces recommendations with evidence and risk notes.
8. Separates measured cost from estimated allocation.

**Acceptance criteria:** Explain the allocation formula, data source, time window and limitations. Do not claim CPU utilisation alone equals actual billed cost.

**Lab safety:** Use a small development cluster, set a budget and delete resources when finished.

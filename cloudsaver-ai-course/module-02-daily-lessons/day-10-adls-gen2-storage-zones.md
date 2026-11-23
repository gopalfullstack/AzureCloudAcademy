# Day 10 – ADLS Gen2 and Storage Zones

**Module:** 02 – Microsoft Azure Cloud and Data Engineering  
**Programme days:** 10  
**Duration:** 3.5 hours

## Learning objective

Design a secure storage layout for raw and curated cost data.

## Detailed topics

1. Storage account and Blob Storage concepts
2. hierarchical namespace
3. ADLS Gen2 containers and directories
4. storage redundancy and access tiers
5. landing/raw/curated/report zones
6. naming and partitioning by date/scope
7. Azure RBAC versus ACLs
8. managed identity
9. SAS risks
10. lifecycle and retention
11. encryption and network controls.

## Where to learn

- [ADLS Gen2 introduction](https://learn.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-introduction)
- [Hierarchical namespace](https://learn.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-namespace)
- [Access control model](https://learn.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-access-control-model)

## Instructor-led practical lab

Create a low-cost development storage account and containers for landing, raw, curated and reports. Define a path convention including source, scope and export date. Upload synthetic files and test least-privilege access.

## Expected deliverables

- [ ] Storage-zone diagram
- [ ] container inventory
- [ ] naming convention
- [ ] sample file paths
- [ ] access test evidence.

## Completion checklist

- [ ] Can explain Blob versus ADLS hierarchical namespace
- [ ] separates immutable source from transformed outputs
- [ ] selects appropriate permissions
- [ ] lab resources are budgeted and cleaned up.

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

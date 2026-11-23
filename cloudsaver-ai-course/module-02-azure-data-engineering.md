# Module 02 – Microsoft Azure Cloud and Data Engineering

**Schedule:** Days 8–15  
**Purpose:** Build a reliable Azure billing-data ingestion path.  
**Outcome:** An automated pipeline that lands, validates and curates cost-export files.

## Learning outcomes

Learners understand Azure resource organisation, Cost Management exports, ADLS Gen2, Event Grid, Azure Functions and data-quality controls.

## Topic-by-topic syllabus

### 2.1 Azure foundations and governance
- Azure regions, availability zones and global infrastructure
- Management groups, subscriptions and resource groups
- Azure Resource Manager and resource providers
- Azure portal, Cloud Shell and Azure CLI
- Resource naming and tagging conventions
- Azure RBAC fundamentals
- Azure budgets, alerts and Cost Management
- Pricing Calculator and cost-aware lab design
- Development versus production environments

**Lab:** Create a dedicated development resource group, apply tags and configure a budget/alert before provisioning services.

### 2.2 Azure Cost Management and exports
- Cost Management scope and terminology
- Actual cost versus amortised cost
- Usage, billing period and charge dimensions
- Cost Analysis views and filters
- Scheduled exports and export destinations
- Export formats and schema inspection
- Subscription, service, resource group and resource dimensions where available
- Credits, refunds, adjustments and currency
- Billing data latency and refresh schedules
- Data provenance and source reconciliation

**Lab:** Download or generate a representative export, inspect its columns and document which fields support each intended report.

### 2.3 Azure Data Lake Storage Gen2
- Storage accounts and Blob Storage
- Hierarchical namespace and ADLS Gen2
- Containers, directories and file paths
- Storage redundancy and access tiers
- Azure RBAC versus data-plane permissions
- Managed identity and secure access patterns
- SAS tokens and their risks
- Python Azure Storage SDK
- Upload, download and list operations
- Lifecycle and retention concepts

**Lab:** Create landing, raw, curated and reports containers. Upload synthetic billing data using Python.

Suggested layout:
```text
cloudsaver-storage/
  landing/azure-cost-exports/
  raw/billing-data/
  curated/daily-cost/
  curated/service-cost/
  curated/resource-cost/
  reports/cost-summary/
```

### 2.4 Event Grid
- Event-driven architecture
- Publishers, topics, subscriptions and handlers
- Storage events and BlobCreated
- Event schemas and payloads
- Event filters
- Delivery, retries and dead-letter concepts
- Duplicate event handling and idempotency

**Lab:** Subscribe to a storage event and inspect the event payload when a new file arrives.

### 2.5 Azure Functions
- Serverless architecture and hosting concepts
- Function Apps and Python programming model
- HTTP, Blob and Event Grid triggers
- Bindings and configuration
- Local development and testing
- Dependencies and deployment packages
- Environment variables and managed identity
- Logging, retries and failure handling
- Cold starts and execution limits at a conceptual level

**Lab:** Implement a function that receives a file-created event, validates the file path and starts processing.

### 2.6 Ingestion, validation and quality
- Source-to-target mapping
- Schema and required-column checks
- Data types and date parsing
- Missing and malformed values
- Duplicate detection
- Currency and date-range checks
- Quarantine of invalid records
- Idempotent processing
- Retry strategy and poison-file handling
- Data quality summary and audit metadata

**Lab:** Build a pipeline that validates each file, moves valid records into curated storage and writes a quality report.

## Eight-day practical sequence

| Day | Focus | Evidence |
|---|---|---|
| 8 | Azure organisation, CLI and budgets | Development environment |
| 9 | Cost Management exports | Export schema notes |
| 10 | ADLS Gen2 | Storage zones |
| 11 | Python Storage SDK | Upload/download script |
| 12 | Event Grid | File-created event |
| 13 | Azure Functions | Event-triggered function |
| 14 | Validation and quarantine | Data quality report |
| 15 | End-to-end integration | Automated ingestion demo |

## Final assignment – Azure Cost Data Pipeline

Build a pipeline that:
1. Receives a synthetic or authorised cost export.
2. Stores the original file with source and timestamp metadata.
3. Triggers processing on file arrival.
4. Validates schema, types, dates and currency fields.
5. Detects duplicates and invalid records.
6. Quarantines invalid input with a reason.
7. Writes curated output and processing logs.
8. Can safely retry without double-counting.

**Acceptance criteria:** Demonstrate successful ingestion, malformed-file handling, retry behaviour, provenance and reproducible output.

**Security:** Use managed identity where supported. Never commit storage keys, SAS tokens or credentials.

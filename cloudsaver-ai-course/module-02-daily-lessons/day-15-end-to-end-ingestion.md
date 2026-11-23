# Day 15 – End-to-End Azure Cost Ingestion Pipeline

**Module:** 02 – Microsoft Azure Cloud and Data Engineering  
**Programme days:** 15  
**Duration:** 3.5 hours

## Learning objective

Integrate storage, event handling, processing and data-quality reporting.

## Detailed topics

1. End-to-end architecture
2. ingestion state and run identifiers
3. landing-to-raw movement
4. event-triggered execution
5. validation pipeline
6. curated outputs
7. idempotent reruns
8. retry and failure recovery
9. audit logs
10. source lineage
11. operational dashboard and runbook.

## Where to learn

- [Azure Well-Architected data management](https://learn.microsoft.com/en-us/azure/well-architected/)
- [Azure Functions monitoring](https://learn.microsoft.com/en-us/azure/azure-functions/functions-monitoring)

## Instructor-led practical lab

Run a complete demonstration: place a synthetic export in landing, trigger processing, validate records, quarantine bad rows, write curated output and produce a run summary. Repeat the same file to prove idempotency.

## Expected deliverables

- [ ] Architecture diagram
- [ ] working ingestion demo
- [ ] run log
- [ ] quality report
- [ ] README and cleanup evidence.

## Completion checklist

- [ ] A repeated event does not double-count
- [ ] source file is retained
- [ ] output is reproducible
- [ ] failures are diagnosable
- [ ] all Azure spend is reviewed and lab resources cleaned.

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

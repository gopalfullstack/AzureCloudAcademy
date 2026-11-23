# Day 12 – Event Grid and Event-Driven Design

**Module:** 02 – Microsoft Azure Cloud and Data Engineering  
**Programme days:** 12  
**Duration:** 3.5 hours

## Learning objective

Trigger processing when a new billing export arrives.

## Detailed topics

1. Event-driven architecture
2. publishers, topics, subscriptions and handlers
3. Storage BlobCreated events
4. event schemas and payloads
5. subject filters
6. delivery semantics
7. retries
8. dead-letter destinations
9. duplicate delivery
10. idempotency keys
11. event observability and troubleshooting.

## Where to learn

- [Event Grid overview](https://learn.microsoft.com/en-us/azure/event-grid/overview)
- [Blob Storage events](https://learn.microsoft.com/en-us/azure/event-grid/event-schema-blob-storage)
- [Event filtering](https://learn.microsoft.com/en-us/azure/event-grid/event-filtering)

## Instructor-led practical lab

Draw the file-arrival event flow. Configure or simulate a BlobCreated subscription, inspect event subject and data fields, filter to the landing path, and design a duplicate-event test.

## Expected deliverables

- [ ] Event-flow diagram
- [ ] sample event payload
- [ ] filter configuration
- [ ] duplicate-handling design.

## Completion checklist

- [ ] Can trace publisher-to-handler flow
- [ ] extracts blob path from event
- [ ] filter excludes irrelevant paths
- [ ] duplicate events cannot cause duplicate billing rows.

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

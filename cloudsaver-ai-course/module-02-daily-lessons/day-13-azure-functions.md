# Day 13 – Azure Functions for Ingestion

**Module:** 02 – Microsoft Azure Cloud and Data Engineering  
**Programme days:** 13  
**Duration:** 3.5 hours

## Learning objective

Build a serverless handler that starts billing-file processing.

## Detailed topics

1. Function App and hosting plan concepts
2. Python programming model
3. triggers and bindings
4. Event Grid trigger versus HTTP trigger
5. local Functions Core Tools
6. app settings
7. dependency management
8. managed identity
9. structured logging
10. retries and poison events
11. timeout and scale considerations
12. deployment basics.

## Where to learn

- [Azure Functions Python guide](https://learn.microsoft.com/en-us/azure/azure-functions/functions-reference-python)
- [Event Grid trigger](https://learn.microsoft.com/en-us/azure/azure-functions/functions-bindings-event-grid-trigger)
- [Local development](https://learn.microsoft.com/en-us/azure/azure-functions/functions-develop-local)

## Instructor-led practical lab

Create a function that receives a storage-created event, validates the container/path, logs event metadata and calls a separate processing function. Test locally with a sample event before cloud deployment.

## Expected deliverables

- [ ] Function source
- [ ] local.settings.example.json without secrets
- [ ] sample event test
- [ ] log output
- [ ] deployment notes.

## Completion checklist

- [ ] Function validates event input
- [ ] business logic is separated from trigger code
- [ ] errors are logged
- [ ] secrets are not committed
- [ ] duplicate event is safely handled.

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

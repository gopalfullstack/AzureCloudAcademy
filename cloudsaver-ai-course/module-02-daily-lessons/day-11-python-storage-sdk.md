# Day 11 – Python and Azure Storage SDK

**Module:** 02 – Microsoft Azure Cloud and Data Engineering  
**Programme days:** 11  
**Duration:** 3.5 hours

## Learning objective

Automate safe upload, listing and download of billing files.

## Detailed topics

1. Python SDK package structure
2. authentication options
3. DefaultAzureCredential concepts
4. local developer login
5. managed identity in Azure
6. BlobServiceClient and container clients
7. upload/download/list
8. metadata and content types
9. retry and timeout behaviour
10. exception handling
11. idempotent naming
12. configuration outside source code.

## Where to learn

- [Azure Storage Python quickstart](https://learn.microsoft.com/en-us/azure/storage/blobs/storage-quickstart-blobs-python)
- [Azure Identity for Python](https://learn.microsoft.com/en-us/python/api/overview/azure/identity-readme)
- [DefaultAzureCredential](https://learn.microsoft.com/en-us/azure/developer/python/sdk/authentication/credential-chains)

## Instructor-led practical lab

Create a Python CLI that authenticates using an approved developer identity, uploads a synthetic export to the landing container, lists files and downloads one for verification. Add metadata and safe error messages.

## Expected deliverables

- [ ] storage_client.py
- [ ] requirements.txt
- [ ] sample upload/download output
- [ ] configuration README.

## Completion checklist

- [ ] Script works without hard-coded keys
- [ ] handles missing files and permission errors
- [ ] upload can be safely repeated
- [ ] metadata and object path are verifiable.

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

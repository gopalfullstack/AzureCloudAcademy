# Day 37 – CloudSaver FinOps Copilot

**Module:** 05 – Generative AI, Microsoft Foundry and RAG  
**Programme day:** 37  
**Duration:** 3.5 hours

## Learning objective

Connect validated cost metrics and retrieved guidance into a read-only assistant.

## Detailed topics

1. Intent and scope extraction
2. structured cost query
3. subscription/date filters
4. validated metric retrieval
5. RAG knowledge retrieval
6. response synthesis
7. evidence and assumptions
8. missing-data response
9. tool/API error handling
10. conversation logging
11. privacy
12. answer evaluation
13. read-only permissions.

## Where to learn

- [Azure Cost Management API](https://learn.microsoft.com/en-us/rest/api/cost-management/)
- [Azure AI Search](https://learn.microsoft.com/en-us/azure/search/search-what-is-azure-search)
- [Foundry documentation](https://learn.microsoft.com/en-us/azure/ai-foundry/)

## Hands-on practical lab

Build a Copilot prototype that answers questions about synthetic subscription spend and retrieves approved AKS guidance. Separate numeric facts from explanatory text and return scope, period, currency and sources.

## Expected deliverables

- [ ] Copilot demo
- [ ] API integration
- [ ] sample questions and answers
- [ ] source trace
- [ ] evaluation notes.

## Completion checklist

- [ ] Numeric values come from validated data tools
- [ ] explanatory content cites knowledge sources
- [ ] assistant states limits
- [ ] no unrestricted Azure credentials or write actions.

## Suggested session timetable

| Activity | Time |
|---|---:|
| Concepts and architecture | 45 min |
| Instructor demonstration | 45 min |
| Guided implementation | 60 min |
| Independent lab and evaluation | 45 min |
| Review and questions | 15 min |
| **Total** | **3.5 hours** |

**AI safety:** Use approved non-sensitive sample data. Treat retrieved documents and user prompts as untrusted inputs. The model must not invent authoritative cost numbers or have unrestricted access to Azure resources.

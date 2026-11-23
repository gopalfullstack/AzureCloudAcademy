# Day 35 – Azure AI Search and Indexing

**Module:** 05 – Generative AI, Microsoft Foundry and RAG  
**Programme day:** 35  
**Duration:** 3.5 hours

## Learning objective

Build a searchable index for CloudSaver's approved knowledge base.

## Detailed topics

1. Search service and index
2. fields and data types
3. keys and filterable fields
4. data sources/indexers concepts
5. vector fields
6. embedding integration
7. keyword search
8. semantic ranking
9. hybrid search
10. filters
11. query configuration
12. search API
13. identity and access control
14. index refresh.

## Where to learn

- [Azure AI Search overview](https://learn.microsoft.com/en-us/azure/search/search-what-is-azure-search)
- [Create vector index](https://learn.microsoft.com/en-us/azure/search/vector-search-how-to-create-index)
- [Hybrid search](https://learn.microsoft.com/en-us/azure/search/hybrid-search-overview)

## Hands-on practical lab

Create an index for approved FinOps policies and AKS runbooks. Implement keyword and vector/hybrid queries, filter by document category and return source metadata with results.

## Expected deliverables

- [ ] Index schema
- [ ] ingestion/indexing script
- [ ] query examples
- [ ] relevance observations.

## Completion checklist

- [ ] Queries return relevant documents
- [ ] filters enforce intended scope
- [ ] source metadata is returned
- [ ] access boundaries are documented.

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

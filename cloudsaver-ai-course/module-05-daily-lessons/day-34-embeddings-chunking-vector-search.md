# Day 34 – Embeddings, Chunking and Vector Search

**Module:** 05 – Generative AI, Microsoft Foundry and RAG  
**Programme day:** 34  
**Duration:** 3.5 hours

## Learning objective

Prepare approved FinOps documentation for semantic retrieval.

## Detailed topics

1. Embedding concept
2. text-to-vector
3. document parsing
4. chunk size and overlap
5. metadata extraction
6. vector dimensions
7. cosine/dot-product similarity concepts
8. indexing
9. nearest-neighbour search
10. keyword versus semantic search
11. hybrid retrieval
12. relevance and ranking
13. document update/deletion.

## Where to learn

- [Azure OpenAI embeddings](https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/understand-embeddings)
- [Azure AI Search vector search](https://learn.microsoft.com/en-us/azure/search/vector-search-overview)
- [RAG overview](https://learn.microsoft.com/en-us/azure/search/retrieval-augmented-generation-overview)

## Hands-on practical lab

Take a small approved set of FinOps runbooks and AKS operating notes. Parse, chunk, attach source/title/version metadata, generate embeddings with an approved model and compare retrieval results for representative questions.

## Expected deliverables

- [ ] Chunked document set
- [ ] embedding/index script
- [ ] retrieval examples
- [ ] chunking decision notes.

## Completion checklist

- [ ] Each chunk retains source metadata
- [ ] retrieval returns relevant passages
- [ ] private or unapproved documents are excluded
- [ ] document updates are considered.

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

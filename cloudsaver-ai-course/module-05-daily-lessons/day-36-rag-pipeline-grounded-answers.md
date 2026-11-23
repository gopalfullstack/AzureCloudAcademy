# Day 36 – RAG Pipeline and Grounded Answers

**Module:** 05 – Generative AI, Microsoft Foundry and RAG  
**Programme day:** 36  
**Duration:** 3.5 hours

## Learning objective

Implement retrieval-augmented generation with evidence attached to every answer.

## Detailed topics

1. RAG request flow
2. document ingestion
3. parsing and chunking
4. embedding generation
5. vector/keyword retrieval
6. ranking
7. context assembly
8. prompt construction
9. response generation
10. citations/source IDs
11. groundedness
12. unsupported question handling
13. retrieval evaluation
14. latency and token cost.

## Where to learn

- [RAG in Azure AI Search](https://learn.microsoft.com/en-us/azure/search/retrieval-augmented-generation-overview)
- [Azure AI Search query guidance](https://learn.microsoft.com/en-us/azure/search/search-query-overview)
- [Evaluate generative AI apps](https://learn.microsoft.com/en-us/azure/ai-studio/concepts/evaluation-approach-gen-ai)

## Hands-on practical lab

Build a Python question-answering flow: accept a question, retrieve relevant passages, construct a grounded prompt, call the model and return answer plus source titles/IDs. Test questions not covered by the documents.

## Expected deliverables

- [ ] RAG API/script
- [ ] retrieval trace
- [ ] answer with source references
- [ ] evaluation test set.

## Completion checklist

- [ ] Answer is supported by retrieved context
- [ ] source references are visible
- [ ] unsupported questions are qualified/refused
- [ ] retrieved content is treated as untrusted input.

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

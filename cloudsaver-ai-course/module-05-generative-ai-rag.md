# Module 05 – Generative AI, Microsoft Foundry and RAG

**Schedule:** Days 31–37  
**Purpose:** Build a grounded AI assistant that explains validated FinOps data using approved knowledge sources.  
**Outcome:** A FinOps Copilot prototype with source-aware answers.

## Learning outcomes

Learners understand LLM concepts, deploy a model through Microsoft Foundry, design prompts, create embeddings, configure Azure AI Search and implement retrieval-augmented generation.

## Topic-by-topic syllabus

### 5.1 Generative AI fundamentals
- AI, machine learning and deep learning overview
- Generative AI and large language models
- Transformer architecture at a conceptual level
- Tokens and tokenisation
- Context windows
- Model parameters and temperature
- System, user and assistant messages
- Model inputs and outputs
- Structured output and JSON
- Model limitations and hallucinations
- Responsible AI and data handling

**Lab:** Compare responses from a model using several controlled FinOps prompts.

### 5.2 Microsoft Foundry
- Foundry projects and resource concepts
- Model catalogue and selection criteria
- Model deployment and endpoints
- Authentication and endpoint configuration
- Python SDK or REST integration
- Inference requests and responses
- Model parameters and structured outputs
- Token consumption and usage limits
- Deployment monitoring
- Model availability and regional considerations
- Cost and quota awareness

**Lab:** Deploy an available model in Microsoft Foundry and call it from a Python application. Verify the current portal and SDK instructions before class.

### 5.3 Prompt engineering
- Prompt structure and instruction clarity
- Role and task definition
- Context provision
- Zero-shot and few-shot examples
- Domain-specific prompt templates
- Output schemas and JSON responses
- Prompt versioning
- Prompt testing and regression cases
- Handling missing or conflicting evidence
- Prompt injection awareness

**Lab:** Create prompts that explain cost trends while requiring the model to distinguish measured facts from hypotheses.

### 5.4 Embeddings and vector search
- Embedding concepts
- Text-to-vector representation
- Chunking and overlap
- Document preprocessing
- Metadata extraction
- Vector dimensions and similarity
- Indexing and retrieval
- Semantic versus keyword search
- Hybrid retrieval
- Filtering and ranking
- Relevance evaluation

**Lab:** Chunk FinOps runbooks and create embeddings for a small approved document collection.

### 5.5 Azure AI Search
- Search service and index concepts
- Index fields and data types
- Data sources and indexers
- Skillsets overview
- Vector fields and vector search
- Embedding integration
- Keyword, semantic and hybrid search
- Filters and metadata
- Query configuration
- Search API integration
- Access control and data boundaries

**Lab:** Create an index of approved FinOps policies, AKS runbooks and operational guidance.

### 5.6 Retrieval-Augmented Generation
- RAG architecture and request flow
- Document ingestion and parsing
- Chunking strategy
- Embedding generation
- Index creation
- Query embedding
- Retrieval and ranking
- Context assembly
- Prompt construction
- Model response generation
- Source references and citations
- Groundedness and refusal behaviour
- Retrieval quality and evaluation

**Lab:** Implement a RAG question-answering service that returns an answer with supporting document references.

### 5.7 CloudSaver FinOps Copilot
- Natural-language query handling
- User intent and scope identification
- Read-only cost data retrieval
- Database query tools
- API integration
- Knowledge retrieval
- Context-aware explanations
- Evidence and assumptions
- Missing-data responses
- Conversation logging
- Response validation and error handling

**Lab:** Build a Copilot that answers questions about synthetic subscription costs and retrieves relevant optimisation runbooks.

## Seven-day practical sequence

| Day | Focus | Evidence |
|---|---|---|
| 31 | LLM fundamentals | Prompt experiments |
| 32 | Microsoft Foundry | Deployed model and API call |
| 33 | Prompt engineering | Versioned prompt library |
| 34 | Embeddings | Embedded document chunks |
| 35 | Azure AI Search | Search index and queries |
| 36 | RAG | Grounded question-answering API |
| 37 | Copilot integration | FinOps Copilot demo |

## Final assignment – CloudSaver FinOps Copilot

Support questions such as:
- What was the selected subscription's spend last month?
- Which services contributed most to the increase?
- What does the approved AKS runbook recommend checking?
- Which cost records support this explanation?

**Acceptance criteria:** Answers must use validated metrics and retrieved documents, show the relevant period and scope, cite or identify retrieved evidence, and clearly state when information is unavailable.

**Safety rule:** The LLM does not calculate authoritative bills, invent cost figures or receive unrestricted Azure credentials.

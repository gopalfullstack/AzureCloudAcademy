# Day 33 – Prompt Engineering and Structured Outputs

**Module:** 05 – Generative AI, Microsoft Foundry and RAG  
**Programme day:** 33  
**Duration:** 3.5 hours

## Learning objective

Design repeatable prompts that explain cost data without inventing facts.

## Detailed topics

1. Task and role definition
2. instruction hierarchy
3. context grounding
4. zero-shot and few-shot examples
5. output constraints
6. JSON schema/structured outputs
7. prompt templates
8. versioning
9. prompt test cases
10. ambiguous inputs
11. conflicting evidence
12. prompt injection awareness
13. safe refusal.

## Where to learn

- [Prompt engineering concepts](https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/prompt-engineering)
- [Structured outputs](https://learn.microsoft.com/en-us/azure/ai-services/openai/how-to/structured-outputs)
- [OWASP LLM Top 10](https://owasp.org/www-project-top-10-for-large-language-model-applications/)

## Hands-on practical lab

Create a versioned prompt that receives validated cost metrics and produces a JSON summary containing facts, scope, period, evidence, assumptions and unknowns. Test incomplete and contradictory input.

## Expected deliverables

- [ ] Prompt template files
- [ ] JSON schema
- [ ] prompt evaluation cases
- [ ] before/after comparison.

## Completion checklist

- [ ] Output validates against schema
- [ ] no cost values are invented
- [ ] missing data is disclosed
- [ ] prompt versions and test results are retained.

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

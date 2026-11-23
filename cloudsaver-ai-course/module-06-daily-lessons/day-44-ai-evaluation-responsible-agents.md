# Day 44 – AI Evaluation and Responsible Agents

**Module:** 06 – AI Agents, Anomaly Detection and Predictive FinOps  
**Programme day:** 44  
**Duration:** 3.5 hours

## Learning objective

Test agent behaviour for accuracy, grounding, security and safe failure.

## Detailed topics

1. Groundedness and relevance
2. factual correctness
3. tool argument validation
4. prompt injection
5. out-of-scope data
6. unsupported questions
7. unsafe action requests
8. evaluation datasets
9. expected outputs
10. regression tests
11. traces
12. human review
13. monitoring and incident handling.

## Where to learn

- [Azure AI evaluation](https://learn.microsoft.com/en-us/azure/ai-studio/concepts/evaluation-approach-gen-ai)
- [OWASP LLM Top 10](https://owasp.org/www-project-top-10-for-large-language-model-applications/)
- [Prompt Shields](https://learn.microsoft.com/en-us/azure/ai-services/content-safety/concepts/jailbreak-detection)

## Hands-on practical lab

Create test cases for normal, ambiguous, unsupported, malicious and cross-scope requests. Run the agent and tools, record expected/actual results, and fix unsafe behaviours before the final demonstration.

## Expected deliverables

- [ ] AI evaluation dataset
- [ ] test results
- [ ] issue log
- [ ] regression suite
- [ ] risk/mitigation summary.

## Completion checklist

- [ ] Agent refuses out-of-scope actions
- [ ] citations/metrics are grounded
- [ ] tool inputs are validated
- [ ] unsafe cases are included in regression tests.

## Suggested session timetable

| Activity | Time |
|---|---:|
| Concepts and design | 45 min |
| Instructor demonstration | 45 min |
| Guided implementation | 60 min |
| Independent lab and evaluation | 45 min |
| Review and questions | 15 min |
| **Total** | **3.5 hours** |

**Safety requirement:** The agent is read-only. Do not give it unrestricted Azure credentials or allow it to approve or execute its own optimisation recommendations. Record evidence, uncertainty and human approval requirements.

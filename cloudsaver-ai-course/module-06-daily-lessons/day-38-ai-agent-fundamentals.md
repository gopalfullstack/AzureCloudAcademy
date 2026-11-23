# Day 38 – AI Agent Fundamentals

**Module:** 06 – AI Agents, Anomaly Detection and Predictive FinOps  
**Programme day:** 38  
**Duration:** 3.5 hours

## Learning objective

Understand agent loops, tool use and safe boundaries for FinOps investigations.

## Detailed topics

1. LLM app versus agent
2. goals and instructions
3. agent loop
4. planning and execution
5. function/tool calling
6. tool schemas
7. orchestration patterns
8. context/state
9. memory boundaries
10. retries and failures
11. traces
12. permission boundaries
13. agent evaluation.

## Where to learn

- [Azure AI Foundry agents](https://learn.microsoft.com/en-us/azure/ai-foundry/agents/overview)
- [Function calling](https://learn.microsoft.com/en-us/azure/ai-services/openai/how-to/function-calling)
- [OWASP LLM Top 10](https://owasp.org/www-project-top-10-for-large-language-model-applications/)

## Hands-on practical lab

Draw an agent flow for investigating a cost spike. Define allowed read-only tools, input schemas, expected outputs, stop conditions and escalation to a human. Simulate a tool failure and an out-of-scope request.

## Expected deliverables

- [ ] Agent flow diagram
- [ ] tool inventory
- [ ] permission matrix
- [ ] test scenarios.

## Completion checklist

- [ ] Can explain each agent step
- [ ] tools are narrowly scoped
- [ ] invalid inputs and failures stop safely
- [ ] human decision points are explicit.

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

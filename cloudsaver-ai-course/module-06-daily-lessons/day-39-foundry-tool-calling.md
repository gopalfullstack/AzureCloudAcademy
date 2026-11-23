# Day 39 – Foundry Agents and Tool Calling

**Module:** 06 – AI Agents, Anomaly Detection and Predictive FinOps  
**Programme day:** 39  
**Duration:** 3.5 hours

## Learning objective

Connect an agent to approved cost, AKS and search tools.

## Detailed topics

1. Foundry agent configuration
2. instructions
3. function definitions
4. typed arguments
5. Python tool integration
6. read-only REST/database tools
7. search tools
8. response schemas
9. tool validation
10. allow-lists
11. authentication
12. execution logs/traces
13. retries/timeouts
14. error messages.

## Where to learn

- [Foundry agents](https://learn.microsoft.com/en-us/azure/ai-foundry/agents/overview)
- [Function calling](https://learn.microsoft.com/en-us/azure/ai-services/openai/how-to/function-calling)
- [Python type hints](https://docs.python.org/3/library/typing.html)

## Hands-on practical lab

Implement tools for subscription spend, AKS workload metrics and anomaly details. Validate dates and subscription scope in code, return structured data and deny unsupported scopes. Connect tools to an agent or simulate the orchestration if access is unavailable.

## Expected deliverables

- [ ] Three read-only tools
- [ ] JSON schemas
- [ ] unit tests
- [ ] agent trace or orchestration log.

## Completion checklist

- [ ] Tool arguments are validated server-side
- [ ] access is scoped
- [ ] tool errors do not fabricate results
- [ ] no write-capable tool is exposed.

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

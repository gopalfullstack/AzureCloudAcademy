# Day 43 – Evidence-Based Recommendation Engine

**Module:** 06 – AI Agents, Anomaly Detection and Predictive FinOps  
**Programme day:** 43  
**Duration:** 3.5 hours

## Learning objective

Turn cost and utilisation findings into actionable recommendations with risk context.

## Detailed topics

1. Recommendation schema
2. evidence and affected scope
3. cost impact estimation
4. assumptions
5. confidence
6. operational/performance risk
7. availability risk
8. ranking
9. policy checks
10. states
11. approval/rejection
12. audit trail
13. before/after measurement
14. estimated savings methodology.

## Where to learn

- [FinOps optimisation](https://www.finops.org/framework/capabilities/workload-optimization/)
- [AKS best practices](https://learn.microsoft.com/en-us/azure/aks/best-practices)
- [Azure Advisor](https://learn.microsoft.com/en-us/azure/advisor/advisor-overview)

## Hands-on practical lab

Generate recommendation records from synthetic cost and utilisation data. Include resource/namespace, evidence window, estimated impact, confidence, risk, suggested validation and required approver. Rank by impact and risk, not savings alone.

## Expected deliverables

- [ ] Recommendation engine
- [ ] JSON schema
- [ ] ranked report/cards
- [ ] risk and confidence test cases.

## Completion checklist

- [ ] Every recommendation has traceable evidence
- [ ] savings are labelled estimates
- [ ] operational risk and approval needs are visible
- [ ] no action is executed.

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

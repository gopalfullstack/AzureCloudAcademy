# Day 56 – Human Approval and Audit Workflow

**Module:** 08 – Security, Testing, Integration and Final Product Development  
**Programme day:** 56  
**Duration:** 3.5 hours

## Learning objective

Implement a traceable review process for recommendations without autonomous production changes.

## Detailed topics

1. Recommendation states
2. review/edit/approve/reject
3. approver identity
4. timestamps and rationale
5. role permissions
6. policy checks
7. audit history
8. separation of recommendation from execution
9. rollback plan
10. post-change verification
11. approval expiration concepts.

## Where to learn

- [Azure RBAC](https://learn.microsoft.com/en-us/azure/role-based-access-control/overview)
- [FastAPI security](https://fastapi.tiangolo.com/tutorial/security/)
- [Audit logging concepts](https://learn.microsoft.com/en-us/azure/azure-monitor/essentials/activity-log)

## Hands-on practical lab

Implement an approve/reject workflow for recommendations. Require an authorised approver, capture rationale and timestamp, prevent self-approval where configured, and show full history. Keep actual Azure write actions disabled.

## Expected deliverables

- [ ] Workflow API/UI
- [ ] state transition diagram
- [ ] audit history
- [ ] permission tests.

## Completion checklist

- [ ] Only authorised approvers can decide
- [ ] each transition is audited
- [ ] recommendation and execution are separate
- [ ] no Azure resource mutation is enabled.

## Suggested session timetable

| Activity | Time |
|---|---:|
| Concepts and review | 45 min |
| Instructor demonstration | 45 min |
| Guided implementation | 60 min |
| Independent lab and validation | 45 min |
| Review and questions | 15 min |
| **Total** | **3.5 hours** |

**Product safety:** Use synthetic or explicitly authorised data. Keep production write actions disabled in the training MVP. Record limitations and require human approval for any future operational change.

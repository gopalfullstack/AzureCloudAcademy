# Day 57 – Automated Testing and Quality Gates

**Module:** 08 – Security, Testing, Integration and Final Product Development  
**Programme day:** 57  
**Duration:** 3.5 hours

## Learning objective

Build an automated test suite for the CloudSaver product's critical flows.

## Detailed topics

1. Test pyramid
2. unit/integration/API/E2E tests
3. pytest
4. fixtures
5. mocks
6. test data isolation
7. database tests
8. contract tests
9. negative/boundary tests
10. regression
11. coverage
12. lint/type checks
13. CI quality gates
14. basic performance tests.

## Where to learn

- [pytest documentation](https://docs.pytest.org/en/stable/)
- [FastAPI testing](https://fastapi.tiangolo.com/tutorial/testing/)
- [Playwright](https://playwright.dev/docs/intro)

## Hands-on practical lab

Write tests for ingestion validation, cost aggregation, AKS allocation formulas, anomaly detection, forecast outputs, Copilot grounding and approval permissions. Run tests in CI and publish results.

## Expected deliverables

- [ ] Test suite
- [ ] CI test run
- [ ] coverage report
- [ ] defects and fixes log.

## Completion checklist

- [ ] Critical calculations and permissions have tests
- [ ] tests are repeatable
- [ ] CI fails on test failure
- [ ] test data contains no sensitive information.

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

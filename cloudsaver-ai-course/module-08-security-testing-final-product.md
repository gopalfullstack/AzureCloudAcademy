# Module 08 – Security, Testing, Integration and Final Product Development

**Schedule:** Days 53–60  
**Purpose:** Integrate and validate the CloudSaver AI prototype.  
**Outcome:** An end-to-end demonstration, technical evidence pack and founder go/revise/pause/stop recommendation.

## Learning outcomes

Learners can test the integrated product, validate financial data, apply security controls, implement a human approval workflow and present a reproducible prototype.

## Topic-by-topic syllabus

### 8.1 Application security
- Secure application architecture
- Entra ID identity and roles
- Least privilege
- Managed identities
- Key Vault and secret handling
- API authentication and authorisation
- Input validation
- SQL injection prevention
- Encryption in transit and at rest
- Sensitive data handling
- Audit logging
- Tenant and scope separation
- Dependency and container security basics

**Lab:** Perform a security review of the development deployment. Remove hard-coded secrets and verify role-based access.

### 8.2 AI security and governance
- Prompt injection and untrusted input
- Malicious content in retrieved documents
- Data leakage risks
- Tool allow-lists and narrow permissions
- Output validation
- Grounding and source evidence
- Unsupported query handling
- Human oversight
- AI evaluation and monitoring
- Model/data handling considerations

**Lab:** Test the Copilot with malicious instructions, unsupported questions and requests for data outside the user's permitted scope.

### 8.3 Software testing
- Testing strategy and test pyramid
- Unit tests
- Integration tests
- API tests
- End-to-end tests
- pytest and fixtures
- Mocking external services
- Test data and isolation
- Database tests
- Pipeline tests
- Negative and boundary tests
- Regression testing
- Coverage and quality gates
- Basic performance testing

**Lab:** Create automated tests for ingestion, cost aggregation, anomaly detection, forecasts and Copilot endpoints.

### 8.4 Financial data validation
- Source-to-target reconciliation
- Billing period and date validation
- Currency consistency
- Credits, refunds and adjustments
- Duplicate records
- Missing records and fields
- Aggregation accuracy
- Resource attribution completeness
- Data freshness
- Provenance and lineage
- Documenting exclusions and assumptions

**Lab:** Compare CloudSaver totals with the selected source export and generate a reconciliation report.

### 8.5 Human approval workflow
- Recommendation lifecycle and states
- Review, edit, approve and reject
- Authenticated approver identity
- Approval timestamp and rationale
- Role-based approval permissions
- Policy checks and allow-lists
- Audit history
- Separation of recommendation and execution
- Rollback planning
- Post-action verification concepts

**Lab:** Implement approve/reject/edit workflow. Keep actual Azure write actions disabled in the MVP.

### 8.6 Dashboard and application integration
- Frontend/backend integration
- Authentication-aware API calls
- Cost KPI cards
- Subscription and service filters
- AKS node and workload views
- Databricks cost views
- Anomaly list and detail view
- Forecast chart and uncertainty
- Copilot conversation interface
- Recommendation cards
- Approval history
- Loading, empty and error states
- Data freshness labels

**Lab:** Connect the dashboard to the backend APIs and demonstrate a complete investigation workflow.

### 8.7 End-to-end product validation
- Full data-to-dashboard flow
- Full data-to-Copilot flow
- Anomaly-to-investigation flow
- Recommendation-to-approval flow
- Access-control testing
- Failure and recovery testing
- Performance and reliability observations
- Cost and resource review
- Known limitations register

**Lab:** Run a scripted end-to-end demonstration using synthetic or explicitly authorised sample data.

### 8.8 Documentation and founder review
- Product overview
- Architecture diagram
- Data-flow diagram
- Infrastructure documentation
- Database schema
- API reference
- Deployment guide
- Security controls
- Test and evaluation reports
- Azure cost estimate and actual usage
- Known limitations and risks
- Customer discovery findings
- Demo presentation
- Go/revise/pause/stop decision

## Eight-day practical sequence

| Day | Focus | Evidence |
|---|---|---|
| 53 | Application security | Security checklist |
| 54 | Financial validation | Reconciliation report |
| 55 | AI security | Prompt-injection test results |
| 56 | Approval workflow | Approval history demo |
| 57 | Automated testing | Test report |
| 58 | Dashboard integration | End-to-end application |
| 59 | Documentation | Technical evidence pack |
| 60 | Final demo and review | Product demonstration and decision |

## Final assignment – CloudSaver AI MVP

Demonstrate:
1. Azure billing data ingestion.
2. Data validation and reconciliation.
3. Cost analytics dashboard.
4. AKS node, namespace and workload analysis.
5. Databricks cost analysis using available sample data.
6. Grounded FinOps Copilot.
7. Anomaly detection and forecast evaluation.
8. Evidence-backed optimisation recommendations.
9. Authenticated human approval and audit history.
10. Secure, repeatable development deployment.

## Final acceptance checklist

- [ ] Selected cost aggregates reconcile to source data.
- [ ] Data period, currency and freshness are visible.
- [ ] AKS allocation method and assumptions are documented.
- [ ] Anomaly tests report false positives and misses.
- [ ] Forecast is compared with a baseline.
- [ ] AI answers use validated metrics and retrieved evidence.
- [ ] Unsupported questions are qualified or refused.
- [ ] User permissions are tested.
- [ ] No autonomous production write action is enabled.
- [ ] Azure spend and resource usage are reviewed.
- [ ] Documentation and demo are reproducible.

## Day-60 founder decision

Recommend moving to a paid pilot only when a recurring customer problem, credible data-access route, user value, acceptable security controls, working evaluated core flow and plausible delivery economics are demonstrated. Otherwise narrow the scope, revise, pause or stop.

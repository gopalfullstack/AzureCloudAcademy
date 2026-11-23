# Module 06 – AI Agents, Anomaly Detection and Predictive FinOps

**Schedule:** Days 38–44  
**Purpose:** Add controlled tool use, anomaly detection, cost forecasting and evidence-based recommendations.  
**Outcome:** A predictive FinOps engine with evaluated analytics and a read-only AI agent.

## Learning outcomes

Learners can connect an agent to approved tools, build a statistical anomaly detector, evaluate a forecast and generate recommendations with evidence and risk.

## Topic-by-topic syllabus

### 6.1 AI agent fundamentals
- LLM applications versus agents
- Agent goals and instructions
- Tool use and function calling
- Agent execution loop
- Tool schemas and typed inputs
- Orchestration patterns
- Context and state
- Memory concepts and boundaries
- Tool errors and retries
- Agent evaluation
- Permission and safety boundaries

**Lab:** Design an agent workflow that can investigate a cost question using a fixed set of read-only tools.

### 6.2 Foundry agents and tools
- Agent setup and configuration
- Instructions and tool definitions
- Function calling
- Python function integration
- Read-only API integration
- Database query tools
- Search tools
- Typed arguments and validation
- Tool response schemas
- Execution logs and tracing
- Access control and allow-lists
- Failure and timeout handling

**Lab:** Create tools for subscription spend, AKS workload metrics and anomaly details. Ensure each tool enforces scope and read-only access.

### 6.3 Cost anomaly detection
- Anomaly definitions and use cases
- Baselines and comparison windows
- Absolute and percentage thresholds
- Moving averages
- Rolling standard deviation
- Seasonality and day-of-week patterns
- Statistical outliers
- Threshold sensitivity
- False positives and false negatives
- Severity classification
- Alert deduplication
- Detection evaluation

**Lab:** Build a Python detector for injected cost spikes in synthetic historical data. Measure detection rate and false positives.

### 6.4 Machine learning foundations
- Supervised and unsupervised learning overview
- Dataset preparation
- Features and labels
- Feature engineering
- Train/test separation
- Model fitting and validation
- Precision, recall and F1
- Overfitting and leakage
- Drift and monitoring
- When a simple rule is preferable to ML

**Lab:** Compare a statistical rule with a simple ML approach on a prepared dataset. Document which performs better and why.

### 6.5 Cost forecasting
- Time-series data structure
- Trends and seasonality
- Missing dates and outliers
- Naive baseline
- Moving average
- Exponential smoothing concepts
- Regression overview
- Forecast horizons
- Daily, weekly and monthly projections
- Backtesting
- Mean Absolute Error and RMSE
- Prediction intervals and uncertainty
- Model limitations and refresh cadence

**Lab:** Forecast 7-, 14- and 30-day expenditure. Compare the result to a naive baseline on held-out data.

### 6.6 Recommendation engine
- Recommendation data model
- Evidence and affected scope
- Cost impact estimation
- Assumptions and confidence
- Risk and performance impact
- Operational and availability risk
- Recommendation ranking
- Policy checks
- Recommendation states
- Approval and rejection reasons
- Audit history
- Post-change measurement concepts

**Lab:** Generate recommendation cards from measured utilisation and cost evidence. Clearly label estimates as estimates.

### 6.7 AI evaluation and responsible use
- Groundedness and relevance tests
- Factual correctness
- Tool input/output validation
- Prompt injection tests
- Unsafe action requests
- Unsupported question handling
- Evaluation datasets
- Regression testing
- Human review
- Logging and monitoring

**Lab:** Build a test set of normal, ambiguous, unsupported and malicious queries. Record expected and actual behaviour.

## Seven-day practical sequence

| Day | Focus | Evidence |
|---|---|---|
| 38 | Agent fundamentals | Agent flow diagram |
| 39 | Tool calling | Read-only tool integration |
| 40 | Anomaly detection | Detector and evaluation |
| 41 | Forecasting | Backtest report |
| 42 | AI explanations | Evidence-grounded summaries |
| 43 | Recommendations | Ranked recommendation cards |
| 44 | Evaluation | AI and analytics test report |

## Final assignment – Predictive FinOps Engine

Deliver:
1. Statistical anomaly detector.
2. Forecasting baseline and backtest.
3. Read-only agent with approved tools.
4. Cost-driver investigation.
5. Recommendation catalogue and ranking.
6. Evidence, assumptions, confidence and risk fields.
7. AI evaluation dataset and results.

**Acceptance criteria:** Demonstrate injected anomalies, report false positives and misses, compare forecast error with a baseline and ensure every recommendation is traceable to evidence.

**Safety rule:** The agent cannot approve or execute its own recommendations.

# Day 7 – Final Project: CloudSaver Billing Processor v1

**Module:** 01 – Python, Git and Software Engineering  
**Duration:** 3.5 hours

## Learning objective

Combine the week's Python, data processing, API and Git skills into a small working application.

## Topics to learn

1. Review the application requirements and input data schema.
2. Read synthetic Azure billing CSV data.
3. Validate required columns and cost values.
4. Handle missing, malformed and duplicate records.
5. Calculate total spend and group by service and resource group.
6. Identify highest-cost resources.
7. Export JSON summary and invalid-row report.
8. Add logging and clear error messages.
9. Document setup and execution.
10. Commit the final version to GitHub.

## Where to learn

- [Pandas user guide](https://pandas.pydata.org/docs/user_guide/index.html)
- [Python logging HOWTO](https://docs.python.org/3/howto/logging.html)
- [GitHub README guidance](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes)

## Hands-on practical lab

Build CloudSaver Billing Processor v1. It must read a synthetic billing CSV, validate its schema, clean and process records, calculate cost summaries, identify high-cost resources, export JSON and invalid-row reports, and log its run. Demonstrate it from a clean environment.

## Expected deliverables

- [ ] Source code and requirements.txt
- [ ] Synthetic sample CSV
- [ ] JSON summary and invalid-row report
- [ ] README with setup and run instructions
- [ ] GitHub repository URL and short demo

## Completion checklist

- [ ] Runs using documented setup steps.
- [ ] Handles malformed input without an unhandled crash.
- [ ] Totals are reproducible and can be manually checked.
- [ ] Invalid rows are separated from valid processed data.
- [ ] No passwords, API keys or confidential billing data are included.

## Suggested class timetable

| Activity | Time |
|---|---:|
| Concepts and explanation | 45 minutes |
| Instructor demonstration | 45 minutes |
| Guided coding | 60 minutes |
| Independent hands-on lab | 45 minutes |
| Review and questions | 15 minutes |
| **Total** | **3 hours 30 minutes** |

**Student instruction:** Complete the practical lab, save your work in your course repository and be ready to explain your solution to the instructor. Use synthetic sample data only; do not upload secrets or confidential billing information.

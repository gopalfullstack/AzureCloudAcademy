# Day 4 – CSV, JSON, NumPy and Pandas

**Module:** 01 – Python, Git and Software Engineering  
**Duration:** 3.5 hours

## Learning objective

Load, clean and analyse tabular billing data.

## Topics to learn

1. Understand why data processing matters in FinOps.
2. Recognise CSV and JSON structures.
3. Learn NumPy arrays and basic operations.
4. Create and inspect Pandas Series and DataFrames.
5. Read CSV and JSON files; inspect columns and data types.
6. Filter, sort and select records.
7. Handle missing and malformed values.
8. Detect duplicates, group records and aggregate costs.
9. Export processed data to CSV and JSON.

## Where to learn

- [Pandas getting started](https://pandas.pydata.org/docs/getting_started/)
- [Pandas introductory tutorials](https://pandas.pydata.org/docs/getting_started/intro_tutorials/)
- [NumPy absolute beginners](https://numpy.org/doc/stable/user/absolute_beginners.html)
- [Python JSON documentation](https://docs.python.org/3/library/json.html)

## Hands-on practical lab

Use a synthetic billing CSV with date, subscription, resource group, service, resource name and cost columns. Inspect the data, identify missing or invalid costs, remove duplicates using a documented rule, and calculate spend by service and resource group.

## Expected deliverables

- [ ] day04_billing_analysis.py
- [ ] cleaned_billing.csv
- [ ] billing_summary.json
- [ ] invalid_rows.csv

## Completion checklist

- [ ] The CSV loads into a DataFrame.
- [ ] Missing and invalid records are handled and reported.
- [ ] Duplicate handling is documented.
- [ ] Grouped totals match a manual check on the sample data.
- [ ] JSON output is valid.

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

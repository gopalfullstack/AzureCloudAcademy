# Module 01 – Python, Git and Software Engineering

**Programme:** CloudSaver AI – Azure Cloud Academy  
**Duration:** 7 days  
**Daily commitment:** 3.5 hours  
**Total learning time:** 24.5 hours  
**Learning approach:** Instructor explanation, demonstration, guided coding and independent lab.

## Module goal

Build the programming and source-control foundation for CloudSaver AI. Learners will create a Python application that reads synthetic Azure billing data, validates and processes it, calculates costs, generates reports and is managed in GitHub.

## Learning outcomes

By the end of this module, learners should be able to:
- Write structured Python programs using functions and classes.
- Work with lists, dictionaries, files, CSV and JSON.
- Process tabular billing data using Pandas.
- Call and test REST APIs.
- Handle errors and create useful logs.
- Use Git and GitHub for version control and collaboration.
- Build and document a small billing-processing application.

---

## Day 1 – Python setup and programming fundamentals

**Duration:** 3.5 hours

### Topics
1. What Python is and where it is used in cloud engineering.
2. Install Python and Visual Studio Code.
3. Configure the Python extension and terminal.
4. Run Python scripts and use the interactive interpreter.
5. Variables, naming conventions and comments.
6. Data types: strings, integers, floats and booleans.
7. Type conversion and operators.
8. Input/output, print and f-strings.
9. Comparisons, Boolean logic and if/elif/else.

### Learning resources
- [Install Python](https://www.python.org/downloads/)
- [Install Visual Studio Code](https://code.visualstudio.com/)
- [Python official tutorial – An Informal Introduction](https://docs.python.org/3/tutorial/introduction.html)
- [LearnPython – interactive beginner exercises](https://www.learnpython.org/)

### Practical lab
Create a command-line cloud resource cost calculator. Ask for a resource name, hourly rate and running hours. Calculate an illustrative cost and print a formatted summary. Use sample values only; this is not an Azure billing calculation.

**Deliverable:** `day01_cost_calculator.py`

---

## Day 2 – Conditions, loops, collections and functions

**Duration:** 3.5 hours

### Topics
1. if, elif and else.
2. for and while loops.
3. break, continue and pass.
4. Lists, tuples, sets and dictionaries.
5. Indexing, slicing and iterating over collections.
6. List and dictionary comprehensions.
7. Defining and calling functions.
8. Parameters, return values and default arguments.
9. Organising reusable code.

### Learning resources
- [Python control flow](https://docs.python.org/3/tutorial/controlflow.html)
- [Python data structures](https://docs.python.org/3/tutorial/datastructures.html)
- [Python functions](https://docs.python.org/3/tutorial/controlflow.html#defining-functions)
- [LearnPython – exercises](https://www.learnpython.org/)

### Practical lab
Use a list of sample Azure resources represented as dictionaries. Calculate total cost, find the most expensive resource, filter resources above a chosen threshold and display a summary.

**Deliverable:** `day02_resources_report.py`

---

## Day 3 – Object-oriented programming, files, exceptions and logging

**Duration:** 3.5 hours

### Topics
1. Modules, imports and code organisation.
2. Classes, objects and constructors.
3. Attributes and methods.
4. Encapsulation and inheritance basics.
5. Composition and reusable design.
6. Reading and writing text files.
7. Context managers and the with statement.
8. try, except, else and finally.
9. Raising exceptions and validating input.
10. Logging levels: DEBUG, INFO, WARNING and ERROR.

### Learning resources
- [Python classes](https://docs.python.org/3/tutorial/classes.html)
- [Python errors and exceptions](https://docs.python.org/3/tutorial/errors.html)
- [Python file input/output](https://docs.python.org/3/tutorial/inputoutput.html)
- [Python logging HOWTO](https://docs.python.org/3/howto/logging.html)

### Practical lab
Create an `AzureResource` class with resource name, resource type and monthly cost. Add a method to calculate annualised cost. Reject invalid costs and log processing events.

**Deliverable:** `day03_azure_resource.py` and a log file.

---

## Day 4 – CSV, JSON, NumPy and Pandas

**Duration:** 3.5 hours

### Topics
1. Why data processing is important in FinOps.
2. CSV and JSON file formats.
3. NumPy arrays and basic operations.
4. Pandas Series and DataFrames.
5. Reading a CSV file and inspecting its columns and data types.
6. Filtering, sorting and selecting rows.
7. Handling missing and malformed values.
8. Finding and removing duplicate records.
9. Grouping and aggregating costs.
10. Exporting results to CSV and JSON.

### Learning resources
- [Pandas – getting started](https://pandas.pydata.org/docs/getting_started/)
- [Pandas – introductory tutorials](https://pandas.pydata.org/docs/getting_started/intro_tutorials/)
- [NumPy – absolute beginners](https://numpy.org/doc/stable/user/absolute_beginners.html)
- [Python JSON documentation](https://docs.python.org/3/library/json.html)

### Practical lab
Process a synthetic Azure billing CSV with fields such as date, subscription, resource group, service, resource name and cost. Clean the data, identify invalid rows and calculate spend by service and resource group.

**Deliverable:** `day04_billing_analysis.py`, cleaned CSV and JSON summary.

---

## Day 5 – REST APIs, HTTP, JSON and Postman

**Duration:** 3.5 hours

### Topics
1. What an API is and why applications use APIs.
2. REST concepts and resource URLs.
3. HTTP methods: GET, POST, PUT, PATCH and DELETE.
4. Status codes, headers and query parameters.
5. JSON objects, arrays and nested responses.
6. Testing requests in Postman.
7. Calling APIs with Python Requests.
8. Timeouts and exception handling.
9. Basic pagination and rate-limit awareness.
10. Safe handling of API keys and credentials.

### Learning resources
- [Postman Learning Centre](https://learning.postman.com/)
- [Python Requests quickstart](https://requests.readthedocs.io/en/latest/user/quickstart/)
- [MDN – HTTP overview](https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview)
- [Microsoft Learn – Azure Cost Management REST API](https://learn.microsoft.com/en-us/rest/api/cost-management/)

### Practical lab
Call a public test API or instructor-provided mock API, inspect its JSON response, extract selected fields and save them to a JSON file. Discuss how authenticated Azure Cost Management APIs can later provide billing data.

**Deliverable:** `day05_api_client.py`

---

## Day 6 – Git and GitHub

**Duration:** 3.5 hours

### Topics
1. Git versus GitHub.
2. Create a GitHub account and repository.
3. Install and configure Git.
4. Initialise or clone a repository.
5. Working tree, staging area and commit history.
6. git status, add, diff, commit, pull and push.
7. Create and switch branches.
8. Merge branches and resolve a simple conflict.
9. Create a pull request.
10. Write a useful README and configure .gitignore.
11. Keep secrets, credentials and private billing data out of source control.

### Learning resources
- [GitHub Skills – Introduction to GitHub](https://github.com/skills/introduction-to-github)
- [GitHub Skills – Introduction to Git](https://github.com/skills/introduction-to-git)
- [GitHub Docs – Git basics](https://docs.github.com/en/get-started/git-basics)
- [Pro Git book – getting started](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control)

### Practical lab
Create a repository named `cloudsaver-billing-processor`. Upload the exercises, create a feature branch, make a change and open a pull request. Add a README and .gitignore. Use synthetic sample data only.

**Deliverable:** GitHub repository with organised source code and documentation.

---

## Day 7 – Final project: CloudSaver Billing Processor v1

**Duration:** 3.5 hours

### Project objective
Integrate the skills from Days 1–6 into a small, repeatable Python application.

### Functional requirements
1. Read a supplied synthetic billing CSV.
2. Check that required columns exist.
3. Validate cost values and handle missing or malformed rows.
4. Detect and remove duplicate records using an agreed rule.
5. Calculate total spend.
6. Group costs by service and resource group.
7. Identify the highest-cost resources.
8. Export a JSON summary and an invalid-row report.
9. Log processing results and errors.
10. Include setup and run instructions in README.
11. Commit the finished application to GitHub.

### Suggested project structure

```text
cloudsaver-billing-processor/
├── data/
│   └── sample_azure_billing.csv
├── src/
│   ├── main.py
│   ├── processor.py
│   └── validator.py
├── reports/
│   ├── monthly_summary.json
│   └── invalid_rows.csv
├── logs/
├── requirements.txt
├── .gitignore
└── README.md
```

### Learning resources
- [Pandas user guide](https://pandas.pydata.org/docs/user_guide/index.html)
- [Python logging HOWTO](https://docs.python.org/3/howto/logging.html)
- [GitHub README guidance](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes)

### Final submission
- Source code and requirements file.
- Synthetic sample input data.
- Generated reports.
- README with installation and execution steps.
- GitHub repository link.
- Short explanation or demonstration of how the application works.

### Acceptance criteria
- Runs from a clean Python environment using documented instructions.
- Handles malformed input without an unhandled crash.
- Produces consistent totals for the supplied sample data.
- Clearly separates invalid rows from processed records.
- Contains no passwords, API keys or confidential billing data.

---

## Daily class timetable

| Activity | Time |
|---|---:|
| Concepts and explanation | 45 minutes |
| Instructor demonstration | 45 minutes |
| Guided coding | 60 minutes |
| Independent hands-on lab | 45 minutes |
| Review and questions | 15 minutes |
| **Total** | **3 hours 30 minutes** |

## Assessment and completion

- Daily coding exercises: 30%
- Practical labs: 30%
- GitHub workflow and documentation: 10%
- Final CloudSaver Billing Processor: 30%

**Completion standard:** Learners should be able to explain their code, run the project independently, show the generated output and demonstrate their GitHub repository.

## Instructor note

This is an intensive seven-day foundation for learners who can dedicate 3.5 focused hours each day. Complete beginners may need 10–14 days, with additional practice. Use synthetic billing data in this module. Connecting real Azure billing accounts and handling credentials should be covered later with appropriate identity, permissions and security controls.

# Module 01 – Python, Git and Software Engineering

**Schedule:** Days 1–7  
**Purpose:** Build the programming and source-control foundation for CloudSaver AI.  
**Outcome:** A Python billing processor committed to GitHub.

## Learning outcomes

By the end of this module, learners can write structured Python programs, process CSV/JSON data, call REST APIs, handle errors and manage source code with Git.

## Topic-by-topic syllabus

### 1.1 Python environment and fundamentals
- Python ecosystem, interpreter and installation
- VS Code setup, terminal and Python extensions
- Virtual environments and package installation
- Variables, naming conventions and basic types
- Strings, integers, floats and booleans
- Type conversion, operators and expressions
- Conditional statements and Boolean logic
- for/while loops, break, continue and pass
- Lists, tuples, sets and dictionaries
- Indexing, slicing and comprehensions

**Lab:** Create a command-line cloud resource cost calculator. Accept resource name, hourly rate and running hours; calculate an illustrative cost and print a formatted summary.

### 1.2 Functions, modules and object-oriented programming
- Function definitions, parameters and return values
- Positional, keyword and default arguments
- Scope and namespaces
- Lambda functions
- Modules, packages and imports
- Classes, objects and constructors
- Attributes and methods
- Encapsulation and inheritance
- Composition and reusable design
- Exceptions, try/except/finally and custom exceptions
- File handling and context managers
- Logging levels and debugging

**Lab:** Create reusable CostRecord and CostCalculator classes. Add validation and structured logging.

### 1.3 Python data processing
- NumPy arrays and basic operations
- Pandas Series and DataFrames
- Reading CSV and JSON
- Inspecting columns, data types and row counts
- Filtering, sorting and selecting data
- Handling null and malformed values
- Duplicate detection and removal
- Type conversion and date parsing
- GroupBy and aggregations
- Joining datasets
- Exporting CSV and JSON

**Lab:** Process a synthetic Azure billing CSV. Calculate spend by subscription, service and resource group. Record invalid rows separately.

### 1.4 REST APIs and JSON
- HTTP and HTTPS fundamentals
- REST principles and resource-oriented URLs
- GET, POST, PUT, PATCH and DELETE
- Headers, query parameters and request bodies
- Common HTTP status codes
- JSON objects, arrays and nested structures
- Python Requests library
- Timeouts, retries and exception handling
- Pagination and rate-limit awareness
- Postman collections and API testing

**Lab:** Call a sample/mock cost API, validate its JSON response and save the result to a file.

### 1.5 Git and GitHub
- Git versus GitHub
- Repository creation and cloning
- Working tree, staging area and commits
- add, status, diff, commit, push and pull
- Branch creation and naming
- Merge and pull-request workflow
- Merge conflict resolution
- .gitignore and README files
- Commit messages and code review basics
- Protecting secrets and sensitive datasets

**Lab:** Create a CloudSaver AI repository, feature branch, pull request and README. Add .env and local data folders to .gitignore.

## Seven-day practical sequence

| Day | Focus | Evidence |
|---|---|---|
| 1 | Python setup, variables, types, conditions | Cost calculator |
| 2 | Loops, collections, functions | Resource cost report |
| 3 | OOP, exceptions, logging, files | Reusable billing classes |
| 4 | Pandas and CSV/JSON processing | Cleaned billing dataset |
| 5 | REST, HTTP, JSON and Postman | API client script |
| 6 | Git, branches and pull requests | GitHub workflow |
| 7 | Integrate and test | Billing processor v1 |

## Final assignment – CloudSaver Billing Processor

Build a Python application that:
1. Reads a supplied synthetic billing CSV.
2. Validates required columns and data types.
3. Handles missing values and duplicate rows.
4. Calculates total spend and grouped cost summaries.
5. Exports a JSON summary and invalid-row report.
6. Logs processing results and errors.
7. Includes a README and repeatable setup instructions.
8. Is committed to GitHub.

**Acceptance criteria:** The program runs from a clean environment, handles malformed input without crashing, produces reproducible totals and contains no secrets.

**Submission:** Source code, sample synthetic input, output files, README and a short explanation of design decisions.

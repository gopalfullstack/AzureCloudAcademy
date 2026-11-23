# Day 5 – REST APIs, HTTP, JSON and Postman

**Module:** 01 – Python, Git and Software Engineering  
**Duration:** 3.5 hours

## Learning objective

Retrieve structured data from an API and process its JSON response.

## Topics to learn

1. Understand APIs, REST and resource-oriented URLs.
2. Learn HTTP methods: GET, POST, PUT, PATCH and DELETE.
3. Understand status codes, headers, query parameters and request bodies.
4. Read JSON objects, arrays and nested structures.
5. Test requests in Postman.
6. Call APIs from Python using Requests.
7. Handle timeouts, HTTP errors and malformed responses.
8. Understand pagination and rate-limit awareness.
9. Keep credentials out of source code.

## Where to learn

- [Postman Learning Centre](https://learning.postman.com/)
- [Requests quickstart](https://requests.readthedocs.io/en/latest/user/quickstart/)
- [MDN HTTP overview](https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview)
- [Azure Cost Management REST API](https://learn.microsoft.com/en-us/rest/api/cost-management/)

## Hands-on practical lab

Call a public test API or instructor-provided mock endpoint. Inspect the response in Postman, then use Python Requests to retrieve JSON, extract selected fields and save them to a file. Discuss how authenticated Azure Cost Management APIs can later supply billing data.

## Expected deliverables

- [ ] day05_api_client.py
- [ ] sample_api_response.json
- [ ] Postman request or collection

## Completion checklist

- [ ] The API request succeeds or reports a clear error.
- [ ] The script checks the HTTP response status.
- [ ] Selected JSON fields are extracted correctly.
- [ ] Timeouts or request errors are handled.
- [ ] No API secrets are committed.

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

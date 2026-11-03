# Seenjoy Academy - API Testing

This project documents API test cases for the Seenjoy Academy application.

## API: Courses

Method: GET

Endpoint:/v1/users/me/courses

Request URL: https://stage-api.seenjoy.academy/v1/users/me/courses?page=1&limit=50

Query Parameters: page=1, limit=50

Expected Status Code: 200 OK

Response FOrmate : JSON

## Test Cases

| Test ID    | Test Scenario              | Expected Result                   |
| ---------- | -------------------------- | --------------------------------- |
| TC_API_001 | Verify API response status | Response status should be 200 OK. |
| TC_API_002 | Verify response format     | JSON                              |
| TC_API_003 | Verify data field exists   | Data field should exist           |
| TC_API_004 | Verify data type           | Data should be an array           |
| TC_API_005 | Verify total field         | Total should be a number.         |

## Tools

Google Chrome DevTools – API request inspection

JavaScript – Automation programming language

Jest – Testing framework

Git and GitHub – Version control

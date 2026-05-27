# FUTURE_CS_03

# API Security Risk Analysis

## Overview

This project demonstrates a basic API Security Risk Analysis conducted on a public demo API using safe and ethical testing methods. The assessment focused on identifying common API security risks such as missing authentication and excessive data exposure.

The analysis was performed for learning purposes as part of the Future Interns Cyber Security Internship 2026.

---

# Objective

The objective of this project was to:

* Understand API security fundamentals
* Analyze public API endpoints
* Identify potential security risks
* Inspect API responses and headers
* Document findings professionally
* Practice security analyst reporting skills

---

# API Tested

JSONPlaceholder Test API

https://jsonplaceholder.typicode.com

---

# Tools Used

* Postman
* GitHub
* MS Word
* Web Browser

---

# Methodology

The following methodology was used during the assessment:

1. Reviewed public API endpoints
2. Sent GET requests using Postman
3. Inspected API responses
4. Observed exposed information
5. Identified potential security risks
6. Classified severity levels
7. Suggested remediation recommendations

---

# Endpoints Tested

## Endpoint 1

GET /posts

## Endpoint 2

GET /users

---

# Key Findings

## 1. Missing Authentication

* The API endpoints were accessible publicly without authentication.
* Data could be retrieved directly through GET requests.

Severity: Medium

---

## 2. Excessive Data Exposure

* User-related information such as names, emails, phone numbers, and websites were publicly accessible.

Severity: High

---

## 3. Authorization Observation

* User-specific information appeared accessible without ownership verification.

Severity: Medium

---

# Recommendations

* Implement authentication mechanisms
* Apply proper access control
* Limit publicly exposed data
* Use secure API design principles

---

# Scope & Ethics

This project involved only safe and read-only testing on public demo APIs.

No exploitation, bypass attempts, harmful actions, or attacks were performed.

---

# Repository Contents

* API_Security_Report.docx
* screenshots/
* README.md

---

# Internship

Future Interns Cyber Security Internship 2026

# FUTURE_CS_03
Cyber Security Internship Task 3 (2026) – Future Interns
📌 Project Overview

This repository contains a professional API Security Risk Analysis Report conducted on public/demo APIs to evaluate modern SaaS security practices.

The objective was to ethically assess API endpoints for:

Authentication weaknesses
Authorization flaws
Excessive data exposure
Missing rate limiting
Input validation issues
Error handling security gaps

This project demonstrates practical cybersecurity consulting skills focused on API security assessment.

🎯 Assessment Objectives
Analyze public/demo APIs
Review authentication requirements
Inspect headers and response structures
Identify API security risks
Classify vulnerabilities by severity
Explain business impact
Recommend remediation strategies
Produce professional security documentation
🛠️ Tools Used
Tool	Purpose
Postman / Insomnia	API testing
Browser DevTools	Header & response inspection
JSONPlaceholder	Public API analysis
ReqRes	Authentication & SaaS security testing
GitHub	Documentation & portfolio
Google Docs / PDF	Final report generation
🔍 APIs Tested
JSONPlaceholder
https://jsonplaceholder.typicode.com/users
/posts
/comments
/users/1
/users/9999
ReqRes
https://reqres.in
/api/login
/api/login/rate
🧪 Methodology
Step 1: API Selection

Selected safe public/demo APIs for legal, read-only testing.

Step 2: Documentation Review

Reviewed:

Authentication
Authorization
Endpoint structures
API key requirements
Error responses
Step 3: Endpoint Testing

Performed:

GET requests
POST validation
Unauthorized access testing
Invalid object requests
Header inspections
Step 4: Security Analysis

Focused on:

Public exposure
Broken authentication
Data leakage
Rate limiting gaps
Error message verbosity
Step 5: Risk Classification

Classified issues as:

Medium
Low-Medium
Low
Informational
🚨 Key Findings Summary
Finding	Severity
Missing authentication on user endpoints	Medium
Excessive data exposure	Medium
Predictable resource enumeration	Low
Missing visible rate limiting	Low-Medium
Verbose auth error leakage	Low
Strong auth enforcement (ReqRes)	Positive
Proper input validation	Positive
💼 Business Impact

Potential risks include:

Sensitive data exposure
Compliance violations
Privacy concerns
API scraping
Unauthorized access attempts
Reconnaissance support for attackers
🛡️ Remediation Recommendations
High Priority
Implement OAuth2/JWT authentication
Enforce role-based access control
Minimize sensitive data exposure
Apply API gateway security
Medium Priority
Add rate limiting
Improve abuse detection
Reduce verbose production error messages
Long-Term
Continuous security audits
Logging & SIEM integration
API governance policies

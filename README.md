# week7_web-application-security-testing
Hands-on web application security testing using Burp Suite and DVWA, covering HTTP request analysis, endpoint discovery, SQL Injection, XSS, and basic vulnerability assessment.

# Week 7: Web Application Security Testing Using Burp Suite

## Project Overview
This project focuses on learning the basics of web application security testing using **Burp Suite Community Edition** and **Damn Vulnerable Web Application (DVWA)** in a controlled lab environment.

## Objective
To understand web application reconnaissance, endpoint discovery, HTTP request analysis, and basic vulnerability testing.

## Lab Environment
- **Operating System:** Kali Linux
- **Testing Tool:** Burp Suite Community Edition
- **Practice Application:** DVWA
- **Environment:** Local virtual lab

## Tools Used
- Burp Suite Community Edition
- DVWA
- Web browser
- Kali Linux

## Tasks Completed
- Set up Burp Suite for HTTP traffic interception.
- Captured and analyzed HTTP requests and responses.
- Explored web application endpoints using Proxy HTTP history.
- Practiced SQL Injection testing in DVWA.
- Explored reflected Cross-Site Scripting (XSS) testing.
- Studied authentication testing and parameter tampering.
- Documented observations and potential security improvements.

## Challenges Faced
- Encountered request-formatting issues while using Burp Suite Repeater.
- Faced limited storage space while setting up an additional practice application.

## Solutions
- Compared browser-generated requests with requests sent through Repeater.
- Used the existing DVWA lab as an alternative practice environment.

## Key Learnings
- Understanding HTTP methods, headers, parameters, and responses.
- Identifying web application endpoints and mapping the attack surface.
- Learning the basics of SQL Injection, XSS, authentication testing, and parameter tampering.
- Understanding the importance of input validation, output encoding, and secure authentication.

## Security Improvements
- Use parameterized queries to prevent SQL Injection.
- Apply context-aware output encoding to reduce XSS risks.
- Implement strong authentication and appropriate rate limiting.
- Validate user input on the server side.
- Follow secure session-management practices.

## Conclusion
This week's practical work improved my understanding of web application security testing and the use of Burp Suite to inspect HTTP traffic and explore potential vulnerabilities. All testing was performed in a controlled DVWA lab environment as part of my cybersecurity learning.

**Internship:** DG InternsHub Cybersecurity Internship

**Disclaimer:** This project is intended for educational purposes. Testing should only be performed on applications and systems for which permission has been granted.

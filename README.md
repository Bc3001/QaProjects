# FirstClient
QA Test
This project showcases my end-to-end QA testing process for a live website for a client. 
The goal was to simulate real-world testing scenarios to identify performance, usability, and stability issues using industry-standard tools.
What I Tested
API Testing: Used Postman to validate response times and endpoint reliability. Retested endpoints if response time exceeded 200ms.

Stress Testing: Simulated 0 to 100 users using Apache JMeter to observe server behavior under load and detect potential performance bottlenecks.

Broken Link Analysis: Ran dead link checks to identify 75+ failed URLs including 403 and 429 errors caused by too many requests and malformed links.

Site Performance Observation: Captured common problematic URLs from Wix backend that may be causing client-side issues.

Tools Used
Postman (API and response time validation)

JMeter (Stress/load testing)

Dead Link Checker (Broken link detection)

Outcome & Recommendations
Identified broken or malformed URLs, excessive requests, and Wix system assets that generate errors.

Recommended reducing redundant asset calls, optimizing Wix settings, and adding retry logic for failed API calls.

Created a full walkthrough video for my QA portfolio.

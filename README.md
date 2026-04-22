# FUTURE_CS_03

## API Security Risk Analysis

##  Project Overview
This project presents an API Security Risk Analysis conducted as part of my Cyber Security Internship at Future Interns. The objective of this assessment was to identify potential security vulnerabilities in publicly accessible APIs and provide recommendations to improve their security posture.

## Objective
- Identify security vulnerabilities in APIs
- Analyze risks associated with insecure endpoints
- Suggest remediation measures to improve API security


##  Target APIs
- https://jsonplaceholder.typicode.com  
- https://reqres.in  

##  Tools Used
- Postman  
- Browser Developer Tools  



## Methodology
- API endpoint testing (GET, POST requests)
- Input validation testing
- Access control testing
- Rate limiting analysis


## Key Findings

### 1. No Authentication & Sensitive Data Exposure (High)
APIs exposed user data without requiring authentication, allowing unauthorized access.

### 2. Broken Access Control (High)
Users' data could be accessed by modifying user IDs in API endpoints.

### 3. No Rate Limiting (Medium)
APIs allowed unlimited requests, making them vulnerable to abuse.

### 4. Verbose Error Messages (High)
Detailed error responses exposed internal API structure and authentication details.

### 5. Missing Input Validation (High)
APIs accepted invalid and empty inputs without proper validation.

##  Recommendations
- Implement authentication mechanisms (API keys, OAuth)
- Enforce proper authorization controls
- Apply rate limiting to API endpoints
- Use generic error messages
- Validate all user inputs strictly
- Use HTTPS for secure communication


## 📌 Conclusion
This project highlights common API security risks and demonstrates how improper implementation can expose sensitive data and system functionality. Implementing proper security measures can significantly reduce these risks.


## 👨‍💻 Author
**Pranav Suresh**  
Cyber Security Intern – Future Interns

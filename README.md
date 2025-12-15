# JSONPlaceholder API – Manual API Testing

## 📌 Project Overview
This project documents a manual API testing effort performed using **Postman** against the **JSONPlaceholder public API**.  
The goal was to validate core API behavior, response status codes, data structures, and error handling for common **GET** and **POST** operations.

Testing was conducted from a **Quality Assurance perspective**, focusing on both positive and negative scenarios rather than backend implementation details.

---

## 🎯 Objectives
- Validate successful data retrieval using GET endpoints  
- Validate resource creation behavior using POST endpoints  
- Verify correct status codes for valid and invalid requests  
- Confirm response body structure and required fields  
- Observe API behavior for invalid or unexpected input  

---

## 🔍 API Under Test
- **Base URL:** https://jsonplaceholder.typicode.com
- **Endpoints Tested:**
  - `GET /posts`
  - `GET /posts/{id}`
  - `POST /posts`

JSONPlaceholder is a **mock API** designed for learning and testing purposes. It simulates API behavior but does not persist data or enforce strict input validation.

---

## 📐 Scope of Testing

### In Scope
- Status code validation (200, 201, 404)  
- Response body structure validation  
- Positive and negative API scenarios  
- Handling of invalid endpoints and non-existent resources  

### Out of Scope
- Authentication and authorization testing  
- Data persistence verification  
- Performance or load testing  
- Security testing  

---

## 🧪 Test Types Performed
- Functional API Testing  
- Positive Testing  
- Negative Testing  
- Error Handling Validation  

---

## 🖥️ Test Environment
- Tool: Postman (Desktop)  
- Platform: API (No UI)  
- Operating System: Windows  

---

## 📄 Test Artifacts
This repository contains the following artifacts:

- **Manual API Test Report (PDF)**  
  - Test cases  
  - Execution results  
  - Coverage summary  

- **Postman Collection**  
  - Saved API requests used during testing  

📎 Files included:
- `JSONPlaceholder API – Manual API Testing Project.pdf`
- `JSONPlaceholder_API_Testing.postman_collection.json`

---

## 🐞 Defects
No functional defects were identified during execution of the test cases.

Invalid request scenarios were handled consistently with the expected behavior of the JSONPlaceholder mock API.

---

## 💡 Notes & Observations
Because JSONPlaceholder is a mock API, POST requests accept missing fields and invalid data types without validation.  
This behavior was documented and treated as expected for the purposes of this project.

In a real production API, stricter input validation would typically be expected.

---

## 📌 Author
Jordyn McIntire
Entry-Level QA Engineer
GitHub: https://github.com/McIntire22





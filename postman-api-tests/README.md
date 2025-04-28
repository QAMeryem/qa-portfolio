# API Testing Portfolio - Postman Collections

Welcome to my API Testing Portfolio! 
This repository showcases my practical skills in **Functional Testing** and **API Automation Testing** using Postman.

---

## Skills Showcased

This portfolio demonstrates the following skills:

- **API Testing:**  
  Hands-on experience with testing RESTful APIs using tools like Postman.
  
- **CRUD Operations:**  
  Proficient in performing Create, Read, Update, and Delete operations with dynamic data inputs.

- **Data-Driven Testing:**  
  Experience in writing tests that iterate over different datasets, validating both valid and invalid data.

- **Authorization & Authentication:**  
  Understanding of various authentication methods (API key, token-based) and the ability to test using pre-request scripts.

- **Environment Variables:**  
  Knowledge of how to use Postman environment variables to keep tests dynamic and reusable across multiple environments.

- **Pre-request Scripts & Automation:**  
  Writing JavaScript to handle pre-request tasks like setting dynamic Authorization headers and configuring test data.

- **Postman Testing Automation:**  
  Ability to use Postman’s Collection Runner and write tests to automate API validation.

---

## Collection Structure

This project contains one main Postman collection:

- **API Testing Portfolio.postman_collection.json**

Inside the collection, you will find organized folders for each type of testing:

### 1. Basic API Tests
- **Basic CRUD:**  
  Create, Read, Update, and Delete operations against a demo API.
- **CRUD Using Variables:**  
  Same operations using environment variables for dynamic URL and API key management.

### 2. Authorization Tests
- Full Authentication Testing against GitHub APIs:
  - No token
  - Invalid token
  - Valid token
  - Pre-request scripts to dynamically set Authorization headers

### 3. Data Driven Tests
- Multiple request runs with varying data inputs.
- Positive and Negative testing scenarios.

---

## Tools & Technologies

- **Postman** for API testing and automation
- **JavaScript** for pre-request and test scripts
- **Postman Collection Runner** for running multiple data-driven tests
- **Environment Variables** for dynamic and reusable requests

---

## How to Run This Project

1. **Clone this repository**:

   ```bash
   git clone https://github.com/yourusername/qa-api-testing-portfolio.git

   ```

2. **Open Postman and Import the collection**:
- API_Testing_Portfolio.postman_collection.json

3. **Set Environment Variables (before running requests)**:
- base_url
- x-api-key
- github_token (for GitHub Authorization tests)

4. **Run Folders or Collections**:
Use Collection Runner or Newman (optional) to automate full runs.

---

## About Me

Hi, I'm Meryem Fatich, passionate about software quality, automation, and crafting robust and scalable tests.

🔗 [LinkedIn Profile](www.linkedin.com/in/meryem-fatich-6177447a)

Feel free to connect with me!

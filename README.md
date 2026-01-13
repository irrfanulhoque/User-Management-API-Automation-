# User Management API Automation

[![GitHub](https://img.shields.io/badge/GitHub-Postman-blue)](https://github.com/irrfanulhoque/User-Management-API-Automation-.git)

Automated **User Management API workflows** in **Postman** using the [ReqRes.in](https://reqres.in/) demo API. The project includes **authentication, CRUD operations, and both positive & negative test scenarios**, demonstrating end-to-end API testing with **dynamic token handling** and **environment variables**.

---

## 🚀 Features

- **Authentication Tests**
  - Login with valid credentials (token extraction)
  - Login with invalid credentials (negative tests)
- **User CRUD Operations**
  - Create User (Valid, No Token, Invalid Data)
  - Update User (Full & Partial)
  - Update User with Invalid ID
  - Delete User (Valid & Already Deleted)
- **Automation Techniques**
  - Environment variables (`token`, `userId`) for dynamic requests
  - Chained requests using **Postman Collection Runner**
  - Positive and negative test validations

---

## 🛠 Tools Used

- [Postman](https://www.postman.com/)  
- [ReqRes.in](https://reqres.in/) – free fake REST API for testing and prototyping  
- JavaScript for **Postman test scripts**  
- JSON files for **collections and environments**

---
## 📂 Repository Structure

- `postman_collection.json` → Contains all requests, test scripts, and workflows.  
- `postman_environment.json` → Contains environment variables used in the collection.  

---

## ⚡ How to Use

1. **Import Collection**
   - Open Postman → `Import` → Choose `User-Management-API-Automation.postman_collection.json`.
2. **Import Environment (Optional)**
   - Open Postman → `Environments` → `Import` → Choose `User-Management-API-Automation.postman_environment.json`.
3. **Run Tests**
   - Select the environment → Open the collection → Click **Run** (Collection Runner) → Execute all requests.
4. **Observe Results**
   - Check test results, tokens, and user IDs dynamically generated during the workflow.

---

## 🔑 Key Highlights

- Real-world scenario of **token-based authentication** (JWT/Bearer)
- End-to-end **API testing automation** using ReqRes demo API
- Covers **positive, negative, and edge cases**
- Uses **environment variables** and **request chaining** for dynamic workflows

---

## 📌 Author

**Irfanul Hoque**  
[GitHub](https://github.com/irrfanulhoque) 

---

## 📄 License

This project is **open source** and available under the MIT License.



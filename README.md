# 🚀 API Testing with Postman & MockAPI

## 📌 Project Overview
This project is a comprehensive **manual & automated API testing suite** using **Postman** and **MockAPI**. It covers all HTTP methods (**GET, POST, PUT, PATCH, DELETE, HEAD, OPTIONS**) with **20+ test cases**, validation scripts, and batch execution using Postman Collection Runner.

## 📌 Tech Stack
- **MockAPI** (for mock REST API)
- **Postman** (for API testing)
- **JavaScript Postman Tests**

## 📌 Features
✅ **20+ Test Cases** covering all HTTP methods  
✅ **Automated Postman Scripts** for validation  
✅ **Batch Execution via Collection Runner**  
✅ **Bug Detection & Error Handling**  

## 📌 Base API URL
```
https://67b9508651192bd378dd1ad1.mockapi.io/api/v1/
```

## 📌 Test Case Summary
| Test Case | Method  | Description |
|-----------|--------|-------------|
| TC01 | GET | Fetch all users |
| TC02 | POST | Create a new user |
| TC03 | PUT | Replace user details |
| TC04 | PATCH | Update a specific field |
| TC05 | DELETE | Remove a user |
| ... | ... | ... |

## 📌 How to Run This Project
### **Option 1: Run Individual Test Cases**
1. Open **Postman**.
2. Select the **MockAPI Collection**.
3. Run each test case manually by clicking **Send**.

### **Option 2: Run Entire Collection in Postman Runner**
1. Open **Postman Collection Runner**.
2. Select the **MockAPI Collection**.
3. Set iteration = 1, delay = 500ms.
4. Click **Run**.

## 📌 Sample Postman Test Script (GET Users)
```javascript
pm.test("Check Status Code", function () {
    pm.response.to.have.status(200);
});
```

## 📌 Lessons Learned
- Understanding **API Testing Fundamentals**
- Writing **Postman Test Scripts (JavaScript)**
- Using **Collection Runner** for batch testing
- Debugging **API errors using Postman Console**

## 📌 Repository Structure
```
📁 MockAPI-Postman-Testing/
 ├── 📄 README.md  (Project Documentation)
 ├── 📂 Postman-Collection/  (Exported Postman collection)
 ├── 📂 Test-Results/  (Screenshots of successful test cases)
 ├── 📂 Scripts/  (JavaScript Postman scripts)
```

## 📌 Next Steps
- ✅ Upload this project to **GitHub**.
- ✅ Add it to **Resume & LinkedIn**.
- ✅ Use this project for **job applications**.

🚀 **Built with ❤️ using Postman, MockAPI & with the help of ChatGPT**


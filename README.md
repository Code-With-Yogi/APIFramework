# 🚀 API Automation Framework

A scalable and maintainable API Automation Framework built using **Java + REST Assured**.  
Designed for enterprise-level API testing with structured architecture, reusable utilities, and CI/CD readiness.

---

## 📌 Project Overview

This framework is designed to:

- Automate REST API test cases efficiently
- Validate complex JSON responses
- Follow scalable automation design principles
- Support CI/CD pipeline integration
- Maintain clean logging and reporting structure

It follows industry best practices and is suitable for real-world enterprise automation projects.

---

## 🛠 Tech Stack

- Java
- REST Assured
- Maven
- TestNG
- Jackson / JSONPath
- Log4j
- Jenkins (CI Integration Ready)

---

## 📂 Project Structure

```
APIFramework/
│
├── src/
│   ├── main/
│   │   └── java/
│   │       ├── base/
│   │       ├── drivers/
│   │       ├── utils/
│   │       └── constants/
│   │
│   └── test/
│       └── java/
│           ├── testcases/
│           └── testdata/
│
├── pom.xml
├── logging.txt
└── .gitignore
```

---

## ⚙️ Key Features

- Structured API request builder
- Centralized configuration management
- Reusable utility classes
- JSON response validation using JSONPath
- Maven-based dependency management
- Clean logging mechanism
- CI/CD friendly framework design

---

## ▶️ How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Code-With-Yogi/APIFramework.git
```

### 2️⃣ Navigate to Project Directory

```bash
cd APIFramework
```

### 3️⃣ Install Dependencies

```bash
mvn clean install
```

### 4️⃣ Execute Test Cases

```bash
mvn test
```

You can also run tests using TestNG XML if configured.

---

## 🔄 CI/CD Integration

This framework can be integrated with:

- Jenkins
- GitHub Actions
- Any CI pipeline that supports Maven execution

---

## 📊 Logging & Reporting

- Execution logs are generated during runtime
- Easily extendable to:
  - Extent Reports
  - Allure Reports
  - Custom HTML Reports

---

## 📈 Future Enhancements

- Data-driven testing support
- Environment-based configuration (QA/UAT/PROD)
- Parallel execution support
- Docker integration
- Allure reporting implementation

---

## 👨‍💻 Author

**Yogesh Dahatonde**  
Software Engineer | API & UI Automation Specialist  

Passionate about building scalable and maintainable automation solutions.

---

## ⭐ Contribution

Feel free to fork this repository and raise pull requests for improvements.

---

### If you find this project useful, please give it a ⭐

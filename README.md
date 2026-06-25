# REST Assured Cucumber API Framework

A Java-based API Automation Framework built using REST Assured, Cucumber BDD, Maven, and POJO classes. This framework is designed to automate REST API testing using reusable components, data-driven testing, and detailed request/response logging.

---

## 🚀 Tech Stack

- Java
- REST Assured
- Cucumber BDD
- Maven
- JUnit
- POJO Serialization & Deserialization
- JSON Path
- Maven Surefire Plugin

---

## ✨ Framework Features

- Cucumber BDD Framework
- REST Assured API Automation
- Reusable Request Specification
- Reusable Response Specification
- POJO Request Payload
- Data-Driven Testing
- Request & Response Logging
- Configuration using Properties File
- Feature Files & Step Definitions
- Maven Build Support

---

## 📁 Project Structure

```
src
├── main
│   └── java
│       └── com.ekanth.automation.api.pojo
│
├── test
│   ├── java
│   │   └── com.ekanth.automation.api
│   │       ├── resources
│   │       ├── runner
│   │       └── stepdefinitions
│   │
│   └── resources
│       ├── features
│       └── global.properties
```

---

## 🧪 Test Scenarios Covered

- Add Place
- Get Place
- Update Place
- Delete Place
- Response Validation
- Status Code Validation
- Response Body Validation

---

## ▶️ Execute the Tests

Run all tests using Maven:

```bash
mvn test
```

Run from Eclipse:

- Right-click **TestRunner.java**
- Run As → JUnit Test

---

## 📊 Framework Components

- Request Specification Builder
- Response Specification Builder
- Utility Classes
- POJO Models
- Feature Files
- Step Definitions
- Hooks
- Configuration Reader

---

## 📦 Maven Commands

Clean Project

```bash
mvn clean
```

Execute Tests

```bash
mvn test
```

Clean & Execute

```bash
mvn clean test
```

Generate Reports

```bash
mvn verify
```

---

## 📌 API Used

This framework uses a public demo REST API for learning and framework demonstration purposes.

---

## 👨‍💻 Author

**Ekanth**

GitHub: https://github.com/ekanth-qa

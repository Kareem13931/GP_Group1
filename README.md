# 🛒 Automation Testing Project – E-Commerce Demo Website

## 📌 Overview
This project is a **UI Automation Testing Framework** built with **Java, Selenium, TestNG, and Maven** following the **Page Object Model (POM)** design pattern.  

It automates test cases for a demo **E-Commerce website** to validate key functionalities such as login, product search, add-to-cart, and checkout.

The goal of this project is to:
- Practice **automation testing** using industry-standard tools.  
- Demonstrate **POM-based test automation framework**.  
- Showcase best practices for maintainable and scalable test automation.  

---

## ⚙️ Tech Stack
- **Language**: Java  
- **Automation Tool**: Selenium WebDriver  
- **Testing Framework**: TestNG  
- **Build Tool**: Maven  
- **Design Pattern**: Page Object Model (POM)  

---

## 📂 Project Structure
ecommerce-automation/
│── src
│ ├── main
│ │ └── java
│ │ └── pages/ # Page classes (POM)
│ ├── test
│ │ └── java
│ │ ├── testcases/ # TestNG test classes
│ │ └── utils/ # Utilities (drivers, configs)
│── pom.xml # Maven dependencies
│── testng.xml # Test suite configuration
│── README.md # Documentation

yaml
Copy code

---

## 🧪 Test Scenarios
The following scenarios are automated:  

✔️ User Login & Logout  
✔️ Product Search & Filter  
✔️ Add to Cart functionality  
✔️ Checkout flow (mock)  
✔️ Validation of error messages and UI elements  

---

## 🚀 How to Run

### 1️⃣ Prerequisites
- Install **Java JDK 11+**  
- Install **Maven**  
- Configure **Selenium WebDriver**  
- Clone this repository:
  ```bash
  git clone https://github.com/your-username/ecommerce-automation.git
  cd ecommerce-automation
2️⃣ Run Tests with Maven
bash
Copy code
mvn clean test
3️⃣ Run Specific Test Suite
bash
Copy code
mvn clean test -DsuiteXmlFile=testng.xml
📊 Reporting
TestNG automatically generates HTML reports inside:

bash
Copy code
test-output/index.html
Reports include test execution results with passed, failed, and skipped test cases.

🎯 Key Features
Page Object Model (POM) implementation for maintainable code.

Cross-browser testing support (Chrome, Firefox, Edge).

Reusable utilities for WebDriver management.

Scalable test framework with easy integration in CI/CD pipelines.

🤝 Contribution
Contributions are welcome!
Fork the repo, create a new branch, add your improvements, and submit a pull request.

📜 License
This project is licensed under the MIT License.

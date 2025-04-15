# 🧪 Demoblaze UI Automation Framework

This project is a complete Selenium-based UI automation framework for testing the product purchase flow on [Demoblaze](https://www.demoblaze.com/).

---

## 📂 Tech Stack

- Java
- Selenium WebDriver
- TestNG
- Page Object Model (POM)
- Log4j for logging
- Extent Reports for reporting
- Maven for build management

---

## 📁 Project Structure

DemoblazeAutomation1/
├── pom.xml
├── README.md
├── testng.xml
├── src
│   ├── main
│   │   ├── java
│   │   │   ├── base
│   │   │   │   └── BaseTest.java
│   │   │   ├── pages
│   │   │   │   ├── CartPage.java
│   │   │   │   ├── CheckoutPage.java
│   │   │   │   ├── HomePage.java
│   │   │   │   ├── LoginPage.java
│   │   │   │   ├── ProductPage.java
│   │   │   │   └── SignUpPage.java
│   │   │   └── utils
│   │   │       ├── ExtentManager.java
│   │   │       └── Utils.java
│   ├── test
│   │   └── java
│   │       └── tests
│   │           └── ProductPurchaseTest.java





### 1. Clone the Repository

```bash
git clone https://github.com/your-username/DemoblazeAutomation1.git
cd DemoblazeAutomation1

2. Import into Eclipse
Open Eclipse → File → Import → Maven → Existing Maven Project → Select the project folder

3. Install Dependencies
If using Maven, right-click project → Maven → Update Project

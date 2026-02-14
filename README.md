# 🛒 BigBasket Automation using Selenium (Java)

## 📌 Project Overview

This project automates key user actions on the **BigBasket website** using **Selenium WebDriver with Java**.  
The automation script simulates a real user workflow including login/signup, manual OTP verification, adding items to the cart, and capturing screenshots of the cart page.

The project demonstrates practical **web automation, dynamic element handling, waits, JavaScript execution, and screenshot capture** techniques used in real-world QA automation.

---

## 🚀 Features

- 🌐 Automatically launches BigBasket website
- 🔐 Login / Sign-Up automation with manual OTP entry
- ⏳ Explicit waits for dynamic web elements
- 🛒 Adds product to cart automatically
- 🖱️ Handles SVG-based cart icon using JavaScript Executor
- 📸 Captures screenshot of cart after adding item
- 🔄 Smooth scrolling and page navigation automation
- 🧹 Automatic browser cleanup after execution

---

## 🛠️ Tech Stack

- **Language:** Java
- **Automation Tool:** Selenium WebDriver
- **Browser:** Google Chrome
- **Build Tool:** Java (JDK)
- **Libraries Used:**
  - Selenium WebDriver
  - ChromeDriver
  - WebDriverWait & ExpectedConditions
  - JavaScriptExecutor
  - Guava Files (Screenshot handling)

---

## 📂 Project Structure

Bigbasket_Automation_Selenium/
│
├── Bigbasketp.java # Main automation script
├── cart_screenshot.png # Captured cart screenshot
└── README.md # Project documentation

---

## ⚙️ Prerequisites

Before running the project, ensure you have:

- Java JDK (8 or above)
- Google Chrome Browser
- ChromeDriver (matching Chrome version)
- Selenium Java libraries added to project

---

🖥️ Automation Workflow

Launch BigBasket website

Wait until page fully loads

Click Login/Sign-Up button

Enter mobile/email

User manually enters OTP in console

Add product to cart

Click cart icon using JavaScript execution

Capture cart screenshot automatically

Close browser session


🤝 Contribution

Contributions are welcome!
Feel free to fork the repository and submit improvements.

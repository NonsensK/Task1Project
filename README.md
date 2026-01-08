# Task 1 – Spring Boot Web Application

## Description
This project is a simple Spring Boot web application demonstrating basic controller usage
and rendering views in a web browser.

The application shows:
- a default greeting page
- a greeting page with a query parameter

---

## How to run
1. Open the project in IntelliJ IDEA
2. Run `Task1ProjectApplication`
3. Open browser and go to:  
   http://localhost:8080

---

## Use cases (browser)

### 1. Home page
**URL:**  
http://localhost:8080

**Result:**  
Displays a simple text message.

![Home page](screenshots/01-home.png)

---

### 2. Greeting page (default)
**URL:**  
http://localhost:8080/greeting

**Result:**  
Displays greeting page with default name.

![Greeting default](screenshots/02-greeting-default.png)

---

### 3. Greeting page with parameter
**URL:**  
http://localhost:8080/greeting?name=Itadori

**Result:**  
Displays greeting page with provided name.

![Greeting with parameter](screenshots/03-greeting-param.png)

---

## Technologies
- Java 21
- Spring Boot
- Thymeleaf

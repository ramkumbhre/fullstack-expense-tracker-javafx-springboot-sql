# 💼 Full-Stack Expense Tracker

A full-stack **Expense Management System** built using **JavaFX** for the desktop UI, **Spring Boot** for the backend REST APIs, and **PostgreSQL** as the database. 
This application allows users to securely track their income and expenses, analyze spending patterns, and visualize data with charts.

---

## 🔍 Features

- **Secure Authentication**  
  - User login and signup system  
  - Role-based access (if applicable)  

- **Expense Tracking**  
  - Add, edit, delete expenses  
  - Categorize expenses (e.g., Food, Travel, Bills, Shopping)  
  - Record income and link with expenses  

- **Calendar View**  
  - Browse expenses by date  
  - Select specific days/weeks/months for detailed expense view  

- **Analytics & Charts**  
  - Real-time charts (bar, pie, line) to analyze spending patterns  
  - Income vs Expense comparison graphs  
  - Monthly / weekly / custom date-range insight  

- **Dashboard Summary**  
  - Display total income, total expenses, savings (income − expenses)  
  - Expense breakdown by category  

- **Database Persistence**  
  - All data stored securely in PostgreSQL  
  - Uses JPA / Hibernate for ORM  

---

## 🧪 Tech Stack

| Layer        | Technology                      |
|---|---|
| **Frontend** | Java + JavaFX                   |
| **Backend**  | Spring Boot (REST APIs)          |
| **Database** | PostgreSQL                       |
| **ORM**      | Hibernate / JPA                  |
| **Build**    | Maven (or Gradle)                 |

---

## 🚀 Getting Started

## fullstack-expense-tracker-javafx-springboot-sql
├── backend/                   # Spring Boot application

│   ├── src/main/java

│   ├── src/main/resources

│   └── pom.xml

├── frontend/                  # JavaFX application

│   ├── src/main/java

│   └── resources/

├── docs/                      # Documentation (optional)

└── README.md                  # This file


### Prerequisites

- Java 17+  
- PostgreSQL 
- Maven or Gradle  
- Git

### Installation & Setup

1. **Clone the repository**  
   ```bash
   git clone https://github.com/ramkumbhre/fullstack-expense-tracker-javafx-springboot-sql.git
   cd fullstack-expense-tracker-javafx-springboot-sql
2. mvn clean package  
   java -jar path/to/your-javafx-app.jar

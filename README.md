<div align="center">

# 🔬 LabSync

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![REST API](https://img.shields.io/badge/REST%20API-FF6B6B?style=for-the-badge)

*Streamlining lab management, one booking at a time 🔬*

</div>

---

## 🧠 About This Project

**LabSync** is a full-stack lab management system built with Java and Spring Boot. It allows students and administrators to manage lab bookings and equipment efficiently through a clean and structured backend system.

---

## ✨ Features

- 📅 Lab booking and scheduling system
- 🔧 Lab equipment management
- 👥 Student and admin role management
- 🔐 Secure authentication and authorization
- 📊 Track equipment availability in real time
- 🗄️ MySQL database for persistent storage

---

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| Java | Core language |
| Spring Boot | Backend framework |
| Spring Security | Authentication & authorization |
| MySQL | Database |
| Hibernate / JPA | ORM & database interaction |
| Maven | Build tool |
| REST API | API architecture |

---

## 🏗️ Architecture

```
Client (Browser / Postman)
    │
    ▼
Spring Boot REST API
    │
    ├── Controllers    → Handle HTTP requests
    ├── Services       → Business logic
    ├── Repositories   → Database operations
    │
    ▼
MySQL Database
```

---

## 📁 Project Structure

```
LabSync/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/labsync/
│   │   │       ├── controller/    # REST controllers
│   │   │       ├── service/       # Business logic
│   │   │       ├── repository/    # JPA repositories
│   │   │       ├── model/         # Entity classes
│   │   │       └── config/        # Security config
│   │   └── resources/
│   │       └── application.properties
├── pom.xml
└── README.md
```

---

## 🚀 Running Locally

```bash
# Clone the repository
git clone https://github.com/AmanJaiswal31/LabSync.git
cd LabSync

# Configure MySQL database
# Open src/main/resources/application.properties
# Update these fields:
spring.datasource.url=jdbc:mysql://localhost:3306/labsync
spring.datasource.username=your_username
spring.datasource.password=your_password

# Build and run
mvn spring-boot:run
# API running at http://localhost:8080
```

---

## 📡 API Reference

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/labs` | Get all labs |
| POST | `/api/labs/book` | Book a lab |
| GET | `/api/equipment` | Get all equipment |
| POST | `/api/equipment/add` | Add new equipment |
| DELETE | `/api/booking/{id}` | Cancel a booking |

---

## 🔮 Future Work

- Add email notifications for booking confirmations
- Add calendar view for lab schedules
- Mobile responsive frontend with React
- Export reports in PDF format

---

## 👨‍💻 Author

**Aman Jaiswal**
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/amanjaiswal31/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:amanjaiswal.cse@gmail.com)

---

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6DB33F,100:4479A1&height=100&section=footer"/>
</div>

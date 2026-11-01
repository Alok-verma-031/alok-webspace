# 🌐 Alok Webspace – Personal Portfolio

Welcome to my personal portfolio website! This project represents my technical skills, projects, and journey as a Java Full Stack Developer.

## 🚀 About the Project

Alok Webspace is a personal portfolio website developed to showcase my profile, technical expertise, completed projects, and contact information.

## ✨ Features

- 👨‍💻 Personal Profile
- 🛠️ Technical Skills
- 📂 Projects Showcase
- 📩 Contact / Enquiry Form
- 💾 Database Integration
- 📱 Responsive User Interface

## 🧑‍💻 Tech Stack

| Technology | Usage |
|---|---|
| Java | Backend Programming |
| Spring Boot | Backend Framework |
| Spring Data JPA | Database Operations |
| Hibernate | ORM |
| MySQL | Database |
| HTML | Structure |
| CSS | Styling |
| JavaScript | Interactivity |

## ⚙️ Installation & Setup

**1. Clone the repository**

```bash
git clone https://github.com/Alok-verma-031/alok-webspace.git
```

**2. Create MySQL Database**

```sql
CREATE DATABASE myportfoliodb;
```

**3. Configure application.properties**

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/myportfoliodb
spring.datasource.username=root
spring.datasource.password=${DB_PASSWORD}

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true

server.port=8282
```

**4. Run the application**

Run the Spring Boot main class from Eclipse or IntelliJ IDEA.

**5. Open in browser**

```text
http://localhost

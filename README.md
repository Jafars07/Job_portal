
# 💼 Job Portal Web Application

A robust and user-friendly **Job Portal** built using **Java Spring Boot** and **Thymeleaf** for full stack development. This platform helps **job seekers** find opportunities and enables **employers** to manage job listings.

---

## 📌 Table of Contents

- [Tech Stack]
- [Features]
- [Installation & Setup]
- [Project Structure]
- [Screenshots]
- [Author]
- [License]

---

## 🛠️ Tech Stack

### 🚀 Backend:
- **Java 17+**
- **Spring Boot**
- **Spring MVC & Security**
- **Spring Data JPA**
- **Hibernate**
- **MySQL**

### 🎨 Frontend:
- **Thymeleaf**
- **HTML5**, **CSS3**
- **Bootstrap 5**

### 🧰 Tools:
- **Maven** (Build tool)
- **Git & GitHub**
- **Postman** (API Testing)
- **IntelliJ / Eclipse**

---

## ✨ Features

### 👤 Job Seekers:
- Register/Login securely
- Browse all job listings
- Apply to available jobs
- Track application history

### 🧑‍💼 Employers:
- Register/Login as company
- Post new job openings
- Manage job listings
- View applicant details

### 🔒 Admin (optional role):
- View all users and job data
- Monitor platform activities

---

## ⚙️ Installation & Setup

> 🧠 Prerequisites:
> - Java 17 or later
> - Maven installed
> - MySQL running

### 📥 1. Clone the Repository

```bash
git clone https://github.com/your-username/job-portal.git
cd job-portal
```

### 🛠️ 2. Configure MySQL Database

Create a database in MySQL named `job_portal_db`.

Then update the following in `src/main/resources/application.properties`:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/job_portal_db
spring.datasource.username=your_mysql_username
spring.datasource.password=your_mysql_password

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQL8Dialect
```

### ▶️ 3. Run the Application

```bash
./mvnw spring-boot:run
```

Now, visit:  
👉 `http://localhost:8080` in your browser

---

## 🗂️ Project Structure

```bash
job-portal/
│
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/yourpackage/
│   │   │       ├── controller/
│   │   │       ├── model/
│   │   │       ├── repository/
│   │   │       └── service/
│   │   ├── resources/
│   │   │   ├── static/
│   │   │   ├── templates/
│   │   │   └── application.properties
│
├── pom.xml
└── README.md
```

---

## 🖼️ Screenshots

![image](https://github.com/user-attachments/assets/167ac598-46c9-4377-8a20-0066d4b4138f)

```
📷 /screenshots/homepage.png
![image](https://github.com/user-attachments/assets/cf84d16a-5c9d-4ffb-9eca-a7a4708415fd)


📷 /screenshots/Login.png
```
![image](https://github.com/user-attachments/assets/00c76ac5-3c9c-421f-89d0-7c4e42b82aec)

📷 /screenshots/register.png

![image](https://github.com/user-attachments/assets/afc39ff8-9004-47b9-853f-fcca290a4700)
📷 /screenshots/job-seeker.png

![image](https://github.com/user-attachments/assets/f978efce-ab6e-4d41-a002-bc965a66bc09)
📷 /screenshots/user profile.png

---

## 👤 Author

**Jafar Sadiq**  
💼 Java Full Stack Developer  
🌐 [LinkedIn](https://linkedin.com/in/jafar-sadiq-53749b281)  
🐙 

---
## 👤 Admin 
 for admin access reach out me!!!!

## 📄 License

This project is licensed under the **MIT License** — feel free to use, modify, and share.

---

## 🙌 Contributions

Pull requests and suggestions are welcome!  
If you find any bugs or want to improve the code, feel free to open an issue or submit a PR.

---

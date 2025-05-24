# 🛒 E-Commerce Platform (Spring Boot, Hibernate, Kafka, REST APIs)

A full-stack, production-ready E-commerce platform designed using **Spring Boot**, **Hibernate**, and **Microservices architecture** with **Kafka-based messaging**, **MySQL**, and **secured endpoints**. Built with scalability, reusability, and modularity in mind.

---

## 🚀 Technical Description

- ✅ **Hibernate ORM** integration: Automatic table generation and schema mapping.
- ✅ **Refactored Service & DAO layers**: Clean separation of concerns and reusable components.
- ✅ **Improved image handling**, **Spring Security bug fixes**, and enhanced role-based access control.
- ✅ IDE compatibility: Runs on **both IntelliJ IDEA & Eclipse** without config conflicts.
- ✅ **Overall codebase redesign** for better modularity and performance.
- ⚠️ *Note: Cart logic and some endpoint mappings are under development.*

---

## 💡 Features

- 🔐 User & Admin authentication with role-based access.
- 🛍 Product catalog, category management, customer list (Admin view).
- 📦 Inventory management, secure product upload with images.
- 🛠 Integrated REST APIs with Swagger documentation.
- 📈 Metrics dashboard & admin workspace.
- 🧩 MVC architecture using `Model`, `Controller`, `View (JSP)`.

---

## 🛠 Tech Stack

| Layer            | Technology                                |
|------------------|--------------------------------------------|
| Backend          | Java, Spring Boot, Spring MVC, Hibernate   |
| Messaging        | Kafka (Planned), RabbitMQ (Planned)        |
| Frontend Views   | JSP, Bootstrap                             |
| Database         | MySQL / MariaDB                            |
| Build Tool       | Maven                                      |
| Dev Tools        | IntelliJ IDEA, Eclipse                     |
| Testing          | JUnit, Postman                             |
| Version Control  | Git + GitHub                               |
| CI/CD            | GitHub Actions (Planned)                   |

---

## 📦 Quickstart

1. **Clone the repository:**
   ```bash
   git clone https://github.com/dasariyadhesh/Ecommerce_Site.git
   cd Ecommerce_Site
   ```

2. **Set up the Database:**
   - Create a new MySQL or MariaDB database (e.g., `ecommerce_db`).
   - Update database credentials in `src/main/resources/application.properties`:

     ```
     spring.datasource.url=jdbc:mysql://localhost:3306/ecommerce_db
     spring.datasource.username=your_db_username
     spring.datasource.password=your_db_password
     ```

3. **Build the Project:**
   ```bash
   mvn clean install
   ```

4. **Run the Application:**
   ```bash
   mvn spring-boot:run
   ```
   The app should be accessible at `http://localhost:8080/`.

5. **Access Swagger Docs:**
   - Visit `http://localhost:8080/swagger-ui.html` for interactive API documentation.

---

## 🧑‍💻 Project Structure

```
Ecommerce_Site/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── yourdomain/
│   │   │           └── ecommerce/
│   │   │               ├── controller/
│   │   │               ├── dao/
│   │   │               ├── model/
│   │   │               ├── service/
│   │   │               └── ...
│   │   ├── resources/
│   │   │   ├── static/
│   │   │   ├── templates/
│   │   │   └── application.properties
│   └── test/
├── pom.xml
└── README.md
```

---

## 🛡 Security

- **Spring Security** is configured for both user and admin roles.
- Default endpoints are secured; ensure user registration/login or set up test credentials in the DB.

---

## 🛠️ Development & Contribution

- Fork the repo, make your changes, and submit a pull request.
- Please ensure unit tests pass before submitting PRs.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙏 Acknowledgements

Thanks to the open-source community and the Spring Boot ecosystem!

---

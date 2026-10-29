# Thesis Assignment Manager

A full-stack web application designed for universities to manage and assign thesis topics to students. Built with a robust Java Spring Boot backend and a MySQL database.

## 📌 Features
* **User Management:** Secure login for Students and Professors.
* **Thesis Workflow:** Professors can post available thesis topics; students can apply and get assigned.
* **Relational Data:** Complex relationships managed via Hibernate (One-to-Many, Many-to-Many).
* **CRUD Operations:** Full Create, Read, Update, Delete functionality for thesis proposals and user profiles.

## 🛠️ Technologies Used
* **Backend:** Java, Spring Boot, Spring MVC, Spring Data JPA
* **Database:** MySQL, Hibernate ORM
* **Frontend:** Thymeleaf / HTML / CSS *(change this if you used React/Angular)*
* **Tools:** Maven, Git

## 🚀 How to Run Locally
1. Clone the repository.
2. Create a MySQL database named `thesis_db`.
3. Update the `src/main/resources/application.properties` file with your MySQL username and password.
4. Run the project using Maven: `mvn spring-boot:run`
5. Open your browser and go to `http://localhost:8080`

## 📸 Screenshots
<img width="1872" height="639" alt="output2" src="https://github.com/user-attachments/assets/bc5fb761-51c2-4a25-942a-469405e3408e" />
<img width="1756" height="964" alt="output3" src="https://github.com/user-attachments/assets/14e4f2e1-915c-4d59-a864-4313aa32cd0b" />

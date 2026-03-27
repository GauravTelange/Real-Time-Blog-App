# Real-Time Blog Application

## 📌 Project Overview
The Real-Time Blog Application is a full-stack web application developed using Spring Boot, Thymeleaf, and MySQL. The platform allows users to register, log in, create blog posts, and search for content dynamically. The application follows the MVC architecture and implements authentication using Spring Security.

## 🚀 Features
- User Registration and Login
- Secure Authentication using Spring Security
- Create, Update, and Delete Blog Posts
- Search Blog Posts
- Responsive UI using Bootstrap
- MVC Architecture Implementation

## 🛠️ Technologies Used
Backend:
- Java
- Spring Boot
- Spring MVC
- Spring Security
- Hibernate / JPA

Frontend:
- HTML
- CSS
- Bootstrap
- Thymeleaf

Database:
- MySQL

Tools:
- IntelliJ / Eclipse
- Postman
- Git & GitHub

## 🏗️ Project Architecture

MVC Pattern

User → Controller → Service → Repository → Database  
                         ↓  
                    Thymeleaf Views

## 📂 Project Structure

src/main/java  
 ┣ controller  
 ┣ service  
 ┣ repository  
 ┣ entity  
 ┣ config  

src/main/resources  
 ┣ templates  
 ┣ static  
 ┣ application.properties

## 🧩 Database Tables

### Users
- id
- name
- email
- password

### Posts
- id
- title
- content
- author
- date

## ▶️ How to Run the Project

1. Clone the repository
2. Open project in IntelliJ or Eclipse
3. Configure MySQL database
4. Update `application.properties`
5. Run Spring Boot Application

## 🎯 Learning Outcomes
- Implemented Spring Boot MVC architecture
- Integrated Spring Security authentication
- Connected backend with MySQL using JPA
- Developed dynamic UI with Thymeleaf

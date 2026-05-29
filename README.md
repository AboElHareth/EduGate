# EduGate

EduGate is a full-stack educational platform designed to help teachers manage their online learning experience without the need to build a custom platform for every course or subject.

The system allows teachers to create and manage courses, upload lectures, create assignments and exams, and generate student accounts based on their subscription package. Students can log into the platform, access course content, submit assignments, and take exams through a clean and user-friendly interface.

---

## Project Idea

Many high school teachers struggle with the high cost and complexity of creating their own educational platforms. EduGate solves this problem by providing a centralized platform where any teacher can subscribe and manage their students and content through a dedicated dashboard.

Instead of creating a separate website for every teacher, EduGate offers a scalable shared platform that supports multiple teachers and thousands of students.

---

## Features

### Teacher Features

* Teacher registration and authentication
* Course creation and management
* Upload lectures and educational materials
* Create assignments and exams
* Generate and manage student accounts
* Monitor enrolled students
* Package-based student limits

### Student Features

* Secure login system
* Access lectures and course materials
* Submit assignments
* Take online exams
* View grades and progress

---

## Technologies Used

### Backend

* ASP.NET Core MVC
* C#
* Entity Framework Core
* SQL Server

### Frontend

* HTML5
* CSS3
* JavaScript
* Bootstrap

### Database

* Microsoft SQL Server

### Tools & Platforms

* Visual Studio
* Git & GitHub
* Docker
* Azure SQL Database

---

## Architecture

The project follows a Layered MVC Architecture to ensure clean code organization and separation of concerns.

### Layers

* Presentation Layer (MVC Controllers & Views)
* Business Logic Layer (Services)
* Data Access Layer (Repositories & EF Core)
* Database Layer (SQL Server)

---

## Project Structure

```text
EduGate/
│
├── Front/                           # Frontend prototype
├── Back/                            # ASP.NET Core MVC application
├── DataBase Diagrams/               # ERD and database scripts
│
└── README.md
```

---

## Database Design

The system uses a relational database designed with normalization and clear entity relationships.

Main entities include:

* Users
* Courses
* Lectures
* Exams
* Questions
* Assignments
* Enrollments
* Packages

Database diagrams are available inside the `DataBase Diagrams` folder.

---

## Team Workflow

* GitHub is used for version control and collaboration.
* The team follows a modular development approach.
* Database migrations are managed using Entity Framework Core.
* Shared cloud database hosted on Azure SQL Database.

---

## Future Improvements

* Payment gateway integration
* AI-generated quizzes
* Mobile application
* Real-time notifications
* Analytics dashboard
* Live streaming support

---

## Educational Purpose

This project is developed as a Graduation Project and Full Stack .NET Training Project to demonstrate practical knowledge in:

* Full Stack Development
* MVC Architecture
* Database Design
* Software Engineering Principles
* Authentication & Authorization
* Cloud-based Development

---

## Authors

EduGate Development Team

---

## License

This project is developed for educational purposes.

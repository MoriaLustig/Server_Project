# Server_Project
# 🎓 Student Grading Platform API

A structured and scalable **ASP.NET Core Web API** for managing student grades in an educational setting.  
Built with clean architecture, secure access, and dynamic business logic — simulating a real-world backend system.

## 💼 About the Project

This project showcases my skills in backend development, clean code, API design, model validation, and system thinking with .NET Core.

It implements a **role-based grading system** where:
- **Teachers** can manage students and grades.
- **Students** can securely view their scores and class performance.

---

## 👩‍🏫 Teacher Features

- Add, update, and delete students  
- Assign or update grades per student or exercise  
- View all student records with their scores  
- Automatically calculate final grades based on configurable weights  

---

## 👩‍🎓 Student Features

- Secure login using ID and password  
- View grades per task or exam  
- See class average for each task  
- View personal final grade based on weighted scores  

---

## 🛠 Tech Stack

- **C# / ASP.NET Core Web API (.NET 6)**
- Layered architecture: Controllers, Services, Data Models  
- Dependency Injection  
- Custom Exceptions & Logging (Console + File)  
- Swagger / Postman for API testing  
- Configuration via `appsettings.json` (no hardcoded logic)  

---

## 🧱 Architecture Highlights

- Clear separation of concerns between API, logic, and data  
- Reusable models and DTOs  
- Centralized configuration for credentials and grading logic  
- Defensive programming using custom exceptions  
- Extensive logging for both user actions and system errors  

---

## 🚀 Run the Project

```bash
git clone https://github.com/MoriaLustig/Server_Project.git
cd Server_Project
dotnet build
dotnet run

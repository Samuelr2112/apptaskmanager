# Task, Contact, and Appointment Management System

A full-stack Java project for managing tasks, contacts, and appointments. Built using Spring Boot (REST API) and vanilla HTML/CSS/JS for the front-end. The system supports adding, deleting, and listing entries in memory, with validation and error handling.

## 🔧 Features

- ✅ Add, delete, and view **Appointments**, **Tasks**, and **Contacts**
- 🧠 In-memory service layer with full data validation
- 🧪 100% test coverage with JUnit
- 🌐 HTML/CSS/JS front-end to interact with the REST API
- 🛠 Modular structure using OOP principles and Spring Boot

## 🚀 Technologies

- Java 17+
- Spring Boot 3+
- REST API (GET, POST, DELETE)
- HTML5 + JavaScript (Fetch API)
- JUnit 5
- H2 (in-memory DB for Spring Boot runtime)

## 📁 Project Structure

src ├── main │ ├── java/com/samuel/appointments/apptaskmanager/ │ │ ├── controllers/ │ │ ├── services/ │ │ ├── models/ │ │ └── ApptaskmanagerApplication.java │ └── resources/static/index.html └── test └── java/com/samuel/appointments/apptaskmanager/ └── (JUnit test files)

markdown
Copy
Edit

## 💻 Usage

1. **Run the Spring Boot App**  
   Inside IntelliJ or from terminal:
   ```bash
   ./mvnw spring-boot:run
Open the front-end
Navigate to:

bash
Copy
Edit
http://localhost:8080/index.html
Use the Web Interface
App Task Manager

Fill in form fields for appointments

Click "Add" to send data via REST API

Click "Delete" to remove them

✅ Example JSON (POST Body)
json
Copy
Edit
{
  "appointmentID": "a01",
  "appointmentDate": "2025-04-30T10:00:00.000+00:00",
  "description": "Meeting with client"
}
🧪 Tests
Run all unit tests:

bash
Copy
Edit
./mvnw test
Tests cover:

AppointmentService

TaskService

ContactService

All model validation logic

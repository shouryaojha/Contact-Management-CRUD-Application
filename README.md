# 📞 Contact Management CRUD Application

A full-stack **Spring Boot Contact Management Application** that allows users to manage contacts with name and phone number using complete **CRUD operations**.  
The application follows a clean layered architecture and includes a simple, responsive frontend.

---

## 🔧 Technologies Used

### Backend
- Java
- Spring Boot
- Spring Web (REST APIs)
- Maven

### Frontend
- HTML
- CSS
- JavaScript (Fetch API)

### Tools
- IntelliJ IDEA
- Postman
- GitHub

---

## 📂 Project Structure
contact-management
│
├── src/main/java/com/example/contact
│ ├── ContactManagementApplication.java
│ ├── controller
│ │ └── ContactController.java
│ ├── service
│ │ └── ContactService.java
│ ├── repository
│ │ └── ContactRepository.java
│ └── model
│ └── Contact.java
│
├── src/main/resources
│ ├── static
│ │ ├── index.html
│ │ ├── style.css
│ │ └── script.js
│ └── application.properties
│
└── pom.xml


---

## 🌐 REST API Endpoints

| HTTP Method | Endpoint | Description |
|------------|----------|-------------|
| POST | `/contacts` | Add a new contact |
| GET | `/contacts` | Get all contacts |
| PUT | `/contacts/{id}` | Update an existing contact |
| DELETE | `/contacts/{id}` | Delete a contact |

---

## 🖥️ Frontend Features

- Add new contact
- View all contacts
- Edit and update contact details
- Delete contact
- Clean and responsive UI
- Real-time update without page reload

---

## ⚙️ Configuration

The application runs on **port 8082**.

```properties
server.port=8082


# Hotel_System

A full-stack hotel management system developed as a personal project.  
It provides core front-desk functionalities:

- Room type and inventory management
- Customer reservation and check-in/out
- Billing and payment recording
- Daily revenue statistics

## Tech Stack

- **Backend:** Spring Boot (Java), Spring Data JPA, Spring Security (optional)
- **Frontend:** Vue 3 + Vite + Pinia (or Vuex) + Vue Router
- **Database:** PostgreSQL
- **Build Tools:** Maven/Gradle (backend), npm/yarn (frontend)
- **API Communication:** RESTful API with JSON (axios on frontend)

## Project Structure

The project is split into two main folders (both in the same repository):
```
Hotel_System/
├── backend/ # Spring Boot application
└── frontend/ # Vue 3 application
```
This separation keeps backend and frontend code clean and independently deployable.
# Space-Connect — Venue & Workspace Booking Platform

### Third Year Project

Space-Connect is a web platform that connects **Venue Owners**, **Event Organizers**, and **Professionals** looking for workspaces. It simplifies space discovery and booking through searchable listings, availability, and direct booking requests.

---

## 1. Project Objective

Space-Connect addresses the problem of finding and booking suitable spaces through scattered channels such as searches, phone calls, and word of mouth.

The platform enables:

* **Venue Owners** — list and manage spaces with pricing, photos, amenities, and availability.
* **Event Organizers** — search and filter venues based on capacity, budget, location, and amenities.
* **Professionals** — find and book desks, meeting rooms, and co-working spaces.

**Goal:** Create a centralized platform for discovering, comparing, and booking spaces efficiently.

---

## 2. Features

### Core Features (MVP)

* User registration and login with **Owner, Seeker, and Admin** roles
* Venue listing **CRUD operations**
* Venue search by keyword, location, capacity, and price
* Filtering and sorting
* Venue details and availability
* Booking request and approval workflow
* Booking status tracking
* Basic user profile management

### Secondary Features

* Availability calendar
* Venue reviews and ratings
* Venue image gallery
* Email/booking notifications
* Wishlist
* Owner–Seeker messaging

### Stretch Features

* Online payment integration
* Map-based venue discovery
* Venue recommendation engine
* Multi-city and multi-language support

---

## 3. Tech Stack

| Layer           | Technology                              |
| --------------- | --------------------------------------- |
| Backend         | **Java, Spring Boot**                   |
| Frontend        | **React**                               |
| Database        | **MySQL**                               |
| API             | **RESTful APIs**                        |
| ORM             | **JPA / Hibernate**                     |
| Build Tool      | **Maven**                               |
| Authentication  | **Spring Security + JWT**               |
| API Testing     | **Postman**                             |
| Version Control | **Git + GitHub**                        |
| Development     | **IntelliJ IDEA**                       |
| Deployment      | **Render / Railway + Netlify / Vercel** |

---

## 4. Project Architecture

Space-Connect follows a **3-tier client-server architecture**:

```text
┌─────────────────────────────┐
│     Presentation Layer      │
│       React Frontend        │
└──────────────┬──────────────┘
               │ REST APIs
┌──────────────▼──────────────┐
│      Application Layer      │
│ Spring Boot Controllers     │
│ Services & Business Logic   │
└──────────────┬──────────────┘
               │ JPA / Hibernate
┌──────────────▼──────────────┐
│        Data Layer           │
│       MySQL Database        │
└─────────────────────────────┘
```

### Backend Structure

```text
com.spaceconnect
├── controller/    → REST endpoints
├── service/       → Business logic
├── repository/    → Data access
├── model/         → JPA entities
├── dto/           → Request/response objects
├── security/      → JWT & role-based access
└── config/        → Application configuration
```

---

## 5. Database Design (Initial Entities)

### Main Entities

* **Users** — user details, role, contact information
* **Venues** — venue details, owner, pricing, capacity, amenities, status
* **VenueImages** — images associated with venues
* **Bookings** — venue, seeker, date/time, and booking status
* **Reviews** — ratings and feedback for completed bookings

### Relationships

```text
User (Owner)  1 ─────── N  Venues
Venue         1 ─────── N  Bookings
Venue         1 ─────── N  VenueImages
User (Seeker) 1 ─────── N  Bookings
Venue         1 ─────── N  Reviews
```

The database uses a relational model with **foreign-key relationships** and is designed for MySQL.

---

## 6. Software Requirements

### Development Tools

* Java JDK 17 / 21
* IntelliJ IDEA
* MySQL Server + MySQL Workbench 
* Git + GitHub
* Postman
* Node.js + npm for the React frontend


## 7. Learning Objectives

This project provides hands-on experience with:

* **Java & OOP**
* **Spring Boot** and dependency injection
* **REST API development**
* **MySQL, JPA & Hibernate**
* **Authentication & authorization with JWT**
* **Git & GitHub development workflow**
* **API testing with Postman**
* **React–backend integration**
* Debugging and problem solving

---

## 8. Future Enhancements

* Real-time availability and double-booking prevention
* Payment gateway integration
* Email, SMS, and WhatsApp notifications
* Admin analytics dashboard
* React Native mobile application
* AI-based venue recommendations
* Location-based and multi-city search

---

## 9. Development Workflow

The project is developed incrementally:

```text
1. Project & Environment Setup
        ↓
2. Database & JPA Entities
        ↓
3. User Registration & Login
        ↓
4. Venue Management APIs
        ↓
5. Booking APIs
        ↓
6. Spring Security + JWT
        ↓
7. API Testing with Postman
        ↓
8. React Frontend Integration
        ↓
9. Secondary Features
        ↓
10. Testing, Deployment & Documentation
```

### Git Practice

Development follows a structured Git workflow with **clear commits**, feature development through a `dev` branch, and stable releases merged into `main`.

---

> **Space-Connect is a practical full-stack project focused on building a real-world booking workflow using Java, Spring Boot, REST APIs, React, and MySQL.**

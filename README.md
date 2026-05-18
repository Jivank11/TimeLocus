# TimeLocus ⏳

**AI-Powered Smart Time Management Web Application**
  Overview

TimeLocus is a **full-stack, AI-powered time management web application** designed to help **students, corporate professionals, and self-employed individuals** efficiently manage their daily schedules, track focused work sessions, organize tasks, and gain intelligent productivity insights.

In today’s digital world, people often struggle with distractions, poor time planning, and ineffective productivity tracking. Existing tools are often either too basic or overly complex, with limited personalization. TimeLocus solves this problem by integrating **Artificial Intelligence (AI)** with modern web technologies to provide **personalized, intelligent, and privacy-focused productivity assistance**.

The system combines:

* **Frontend:** Next.js 14 + React 18
* **Backend:** Spring Boot 3 + Spring Security
* **Authentication:** JWT (JSON Web Token)
* **Database:** MySQL
* **AI Assistant:** Ollama (Local LLM Runtime)
* **ORM:** Spring Data JPA
* **Connection Pooling:** HikariCP

TimeLocus provides users with a responsive interface for time tracking, task management, productivity analysis, and AI-driven coaching — all within a secure and scalable architecture.

---

## 🚀 Features

### 1. Real-Time Time Tracker

* Start, pause, and stop live work sessions.
* Manual time entry support.
* Session history tracking.
* Deep work monitoring.

### 2. Weekly Planner

* Organize daily and weekly activities.
* Event categorization.
* Schedule planning for study or work.

### 3. Task Manager

* Create and manage tasks.
* Set task priorities (Low, Medium, High).
* Task completion tracking.
* Deadline organization.

### 4. Focus Zone (Pomodoro Technique)

* Focus timer implementation.
* Work-break session management.
* Productivity-focused workflow.

### 5. Progress Dashboard

* Productivity analytics.
* Visual reports and insights.
* Daily and weekly performance tracking.
* Focus score visualization.

### 6. AI Productivity Assistant

* Personalized productivity coaching.
* Intelligent study recall question generation.
* Daily productivity insights.
* Context-aware guidance based on user roles.

---

## 🧠 Focus Score Algorithm

TimeLocus includes a proprietary **Focus Score Algorithm** that measures productivity based on:

* **Deep work duration**
* **Break patterns**
* **Task switching frequency**
* **Session consistency**

The score helps users understand their productivity habits and improve focus over time.

---

## 🏗️ System Architecture

TimeLocus follows a **Three-Tier Client-Server Architecture**:

### 1. Presentation Layer (Frontend)

Built using:

* Next.js 14
* React 18
* Responsive UI components

Responsibilities:

* User Interface rendering
* API communication
* Real-time timer handling
* Dashboard visualization

### 2. Business Logic Layer (Backend)

Built using:

* Spring Boot 3
* Spring Security
* REST APIs

Responsibilities:

* Authentication & authorization
* Task management
* Planner services
* Time tracking logic
* AI request handling

### 3. Data Layer (Database)

Built using:

* MySQL
* Spring Data JPA
* HikariCP

Responsibilities:

* Data storage
* Relationship management
* Query optimization
* Persistent user data

---

## 🔐 Security Features

TimeLocus implements strong security practices:

* JWT-based stateless authentication
* Spring Security integration
* Role-Based Access Control (RBAC)
* Secure API access
* Password encryption
* Session-independent authorization

---

## 🤖 AI Integration (Ollama + Local LLM)

TimeLocus uses **Ollama**, a local LLM runtime, to enable **offline and private AI inference**.

### Supported AI Capabilities

* Productivity coaching
* Study recall question generation
* Smart daily insights
* Personalized suggestions

### Benefits of Local AI

* Privacy-focused
* No external API dependency
* Offline functionality
* Faster local responses
* Lower operational cost

Example models:

* LLaMA 3
* Mistral
* Gemma

---

## 🛠️ Tech Stack

### Frontend

* React 18
* Next.js 14
* HTML5
* CSS3
* JavaScript / TypeScript

### Backend

* Java
* Spring Boot 3
* Spring Security
* Spring Data JPA
* RESTful APIs

### Database

* MySQL
* HikariCP Connection Pooling

### Authentication

* JWT Authentication

### AI Integration

* Ollama
* Local LLM Models

### Development Tools

* IntelliJ IDEA / VS Code
* Postman
* MySQL Workbench
* Git & GitHub

---

## 📂 Project Modules

```text
TimeLocus
│── Frontend (Next.js + React)
│── Backend (Spring Boot)
│── Authentication Module
│── Task Management Module
│── Weekly Planner Module
│── Focus Zone Module
│── Dashboard Analytics Module
│── AI Assistant Module (Ollama)
│── Database (MySQL)
```

---

## ⚙️ Installation & Setup

### Prerequisites

Make sure you have installed:

* Node.js (18+)
* Java JDK 17+
* MySQL Server
* Maven
* Ollama
* Git

### 1. Clone Repository

```bash
git clone <repository-url>
cd timelocus
```

### 2. Setup Frontend

```bash
cd frontend
npm install
npm run dev
```

### 3. Setup Backend

```bash
cd backend
mvn clean install
mvn spring-boot:run
```

### 4. Configure Database

Create a MySQL database:

```sql
CREATE DATABASE timelocus;
```

Update:

```properties
application.properties
```

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/timelocus
spring.datasource.username=root
spring.datasource.password=your_password
```

### 5. Run Ollama

Install and start Ollama:

```bash
ollama run llama3
```

---

## 📊 Core Functionalities

| Module         | Purpose                        |
| -------------- | ------------------------------ |
| Time Tracker   | Track productive work sessions |
| Task Manager   | Manage tasks with priorities   |
| Weekly Planner | Organize schedules             |
| Focus Zone     | Pomodoro productivity sessions |
| Dashboard      | Productivity analytics         |
| AI Assistant   | Smart guidance and coaching    |

---

## 🎯 Target Users

TimeLocus is designed for:

### Students

* Study planning
* Recall question generation
* Focus tracking

### Corporate Professionals

* Meeting planning
* Productivity optimization
* Time utilization insights

### Self-Employed Individuals

* Project time tracking
* Work organization
* Productivity coaching

---

## 🧪 Testing

The application was tested for:

* Authentication validation
* API integration
* Database consistency
* Timer accuracy
* Dashboard analytics
* AI response handling
* User interface responsiveness

---

## 📈 Future Enhancements

* Mobile application support
* Calendar synchronization
* Voice-enabled AI assistant
* Team collaboration features
* Smart notifications
* Advanced productivity forecasting

---

## ✅ Conclusion

TimeLocus is a modern AI-powered productivity platform that combines **time tracking, planning, analytics, and intelligent assistance** into one unified system. By integrating **Next.js, Spring Boot, MySQL, JWT security, and Ollama-powered local AI**, the application provides users with a secure, scalable, and privacy-focused productivity solution suitable for students, professionals, and freelancers.

---

## 👨‍💻 Authors

**Project Name:** TimeLocus

Developed as a modern full-stack AI-integrated productivity management system.


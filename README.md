# 🚀 Software Project Management Tool

A web-based **Software Project Management Tool** designed to simplify software project planning, task tracking, requirements management, and cost estimation. The application brings essential project management activities together in one place to support a more organized software development lifecycle.

🔗 **GitHub Repository:** [Software Project Management Tool](https://github.com/Soumik-011204/Software_Project_Management_Tool)

## 📌 Project Overview

Managing a software project involves coordinating tasks, maintaining requirements, monitoring progress, and estimating development costs and effort. This project aims to provide a centralized platform for handling these activities efficiently.

The system includes a dashboard, a Kanban board, a requirements management module, and a COCOMO-based estimation module.

## ✨ Features

- 📊 **Dashboard** — Centralized interface for accessing project information.
- 📋 **Kanban Board** — Visual task management and workflow tracking.
- 📝 **Requirements Management** — Organize and manage software project requirements.
- 🧮 **COCOMO Estimation** — Estimate software development effort and schedule using the Constructive Cost Model.
- 🔐 **Authentication** — Firebase Authentication integration.
- ☁️ **Database Management** — Firebase Firestore integration for application data.

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| HTML5 | Web page structure |
| CSS3 | Styling and layout |
| JavaScript | Frontend functionality |
| Node.js | Server-side runtime |
| Express.js | Backend framework |
| Firebase Authentication | User authentication |
| Firebase Firestore | Database |
| Git & GitHub | Version control and collaboration |

## 📂 Project Modules

### 1. Dashboard
Provides a centralized interface for navigating the application and viewing relevant project information.

### 2. Kanban Board
Organizes tasks into workflow stages to make task tracking and project progress easier to understand.

### 3. Requirements Management
Supports the organization and management of software requirements throughout the development process.

### 4. COCOMO Estimation
Uses the Constructive Cost Model (COCOMO) approach to support software effort and schedule estimation based on project inputs.

## 🏗️ System Architecture

The application follows a web-based client-server approach.

```text
           User
             |
             v
      Web Interface
    (HTML, CSS, JavaScript)
             |
             v
      Node.js / Express
             |
             v
       Firebase Services
       /              \
      v                v
Authentication      Firestore
```

*Note: This is a conceptual architecture; the exact data flow depends on the implemented code.*

## ⚙️ Installation and Setup

### Prerequisites

- [Git](https://git-scm.com/)
- [Node.js and npm](https://nodejs.org/)
- A Firebase project configured for the application

### Step 1: Clone the Repository

```bash
git clone https://github.com/Soumik-011204/Software_Project_Management_Tool.git
```

### Step 2: Navigate to the Project

```bash
cd Software_Project_Management_Tool
```

### Step 3: Install Dependencies

Run the following command in the directory containing the relevant `package.json` file:

```bash
npm install
```

If the frontend and backend use separate package files, install dependencies in each respective directory.

### Step 4: Configure Firebase

1. Open the [Firebase Console](https://console.firebase.google.com/).
2. Create or select a Firebase project.
3. Enable Firebase Authentication with the providers required by the application.
4. Configure Cloud Firestore.
5. Add the necessary Firebase configuration and environment variables as expected by the source code.

**Security:** Never commit private keys, service-account credentials, or sensitive environment variables to GitHub.

### Step 5: Run the Application

Use the start script defined in the relevant `package.json`. For example:

```bash
npm start
```

For projects configured with a development script:

```bash
npm run dev
```

The correct command depends on the actual project configuration.

## 🎯 Objectives

- Simplify software project management.
- Improve task organization and progress tracking.
- Provide a structured approach to requirements management.
- Support software development effort and schedule estimation.
- Apply software engineering concepts in a practical web application.

## 🔮 Future Enhancements

- Role-based access control.
- Real-time collaboration and notifications.
- Advanced project analytics and progress reports.
- Requirement traceability and change tracking.
- Exportable COCOMO estimation reports.
- Automated testing and deployment.

## 🎓 Academic Context

Developed as an academic Software Engineering project to apply concepts of web development, project planning, requirements management, and software cost estimation.

## 👨‍💻 Author

**Soumik Sarkar**

- GitHub: [@Soumik-011204](https://github.com/Soumik-011204)

## 📄 License

No license has been specified in this README. Add a suitable open-source license if you intend to distribute the project under specific reuse terms.

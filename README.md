# 💻 VelocityPad | Real-Time Collaborative Development Environment

**VelocityPad** is a high-performance, multi-user collaborative code editor and compiler designed for seamless pair programming. Built with the **MERN stack**, **Socket.io**, and **GROQ AI**, it allows developers to write, execute, and debug code in a synchronized environment with integrated communication tools.

---

## 🎓 Viva Submission Details
> **Note to Supervisor:** This repository is structured as per the mandatory guidelines for the Final Viva.

* **Project Title:** Real-Time Collaborative Development Environment
* **Project Type:** Copyright (Application Filed)
* **Team Details:**
    * **Name:** Durgesh Kumar | **Roll Number:** [2210991551]
* **Submission Status:** Final Submission
* **Supervisor/Collaborator Access:** shikha.1290@chitkara.edu.in

---

## 🚀 Live Demo
Experience real-time collaboration here:  
👉 **[VelocityPad Live on Vercel](https://velocitypad.in/)**

---

## 🌟 Key Features
* **Real-Time Collaboration:** Instantaneous code synchronization across all users using WebSockets.
* **Integrated Communication:** * **Live Chat:** Real-time text messaging within the coding room.
    * **Voice Call:** Built-in audio communication for seamless pair programming.
* **AI Debugging & Optimization:** Powered by **GROQ AI** to analyze code logic and provide instant fixes for errors.
* **Multi-Language Support:** Execute code in Python, Java, C++, and JavaScript (Node.js).
* **Advanced Editor Tools:**
    * **File Upload:** Import existing code files directly into the editor.
    * **Save to File:** Export your collaborative work to your local machine.

---

## 🛠️ Technical Stack
| Layer | Technology |
| :--- | :--- |
| **Frontend** | React.js, Tailwind CSS, Monaco Editor |
| **Backend** | Node.js, Express.js |
| **Real-Time** | Socket.io (WebSockets) |
| **Email Service** | SendGrid |
| **AI Integration** | GROQ Cloud API |

---

## 📂 Project Structure (As per Guidelines)
```text
Project Title (Roll Numbers)/
├── Source Code/             # Core Project Implementation
│   ├── Backend/             # Express.js Server logic
│   └── frontend/            # React.js Client (Vite)
├── Report/                  # Final Documentation
│   ├── Final_Report.pdf     # Project Final Report
│   └── Presentation.pptx    # Viva Presentation (PPT)
├── Documents/               # Legal & Submission Records
│   ├── Copyright_Form.pdf   # Filed Copyright Application
│   ├── Diary_Number.png     # Screenshot of Submission Status
│   └── PIE_CIE_Forms.pdf    # Academic Forms
└── README.md                # Project Overview

## 💻 Local Setup & Installation

Follow these steps to get the project running locally:

### 1. Clone the Repository
```bash
git clone [https://github.com/Durgesh1008/CodeSyncRealTimeCodeCompilar.git]
cd "Source Code"
```
### 2. Install Dependencies
## For the Backend:

```Bash
cd server
npm install
```
## For the Frontend:

```Bash
cd ../client
npm install
```

### 3. Environment Variables
## Create a .env file in the server directory:

```Bash
PORT=5000
NODE_ENV=development
GROQ_API_KEY=your_groq_key
SENDGRID_API_KEY=your_sendgrid_key
FRONTEND_URL=your_frontend_url (for sending invitation mail)
```

### 4. Run the Project
## Start Backend:
# Inside /server
```Bash
npm run dev
```

## Start Frontend:
# Inside /client
```Bash
npm start
```

## ⚖️ Intellectual Property & Copyright

This project is officially registered for copyright with the Government of India.

- **Status:** Copyright Application Filed (Pending)
- **Diary Number:** [SW-18572/2026-CO]
- **Date of Application:** April 23, 2026
- **Class of Work:** Computer Software
- **Author:** Durgesh Kumar

> **Note:** The "AI Activation Logic" and unique real-time synchronization architecture are protected under this application. Any unauthorized reproduction or distribution of this source code is strictly prohibited.



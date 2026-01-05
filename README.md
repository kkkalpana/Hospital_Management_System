# 🏥 MediCare Plus - Hospital Management System

<div align="center">

![MediCare Plus](https://img.shields.io/badge/MediCare-Plus-blue?style=for-the-badge)
![React](https://img.shields.io/badge/React-19.1.1-61DAFB?style=for-the-badge&logo=react&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-Express-339933?style=for-the-badge&logo=node.js&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

**A comprehensive, modern healthcare management platform designed to streamline hospital operations and enhance patient care.**

[Features](#-key-features) • [Installation](#-installation--setup) • [Demo](#-screenshots) • [Tech Stack](#-technology-stack) • [Contributors](#-team-members)

</div>

---

## ⚠️ Disclaimer

> **Important Notice:** This project is developed for educational and demonstration purposes only. It is **NOT** intended for use in production healthcare environments without proper medical compliance certifications, HIPAA compliance audits, security assessments, and legal reviews. 
> 
> **Do not use this system to store or manage real patient data** without ensuring full compliance with healthcare regulations (HIPAA, GDPR, etc.) and implementing proper security measures including data encryption, secure authentication, audit logging, and regular security assessments.

---

## 📋 Table of Contents

- [Abstract](#-abstract)
- [Project Description](#-project-description)
- [Key Features](#-key-features)
- [Technology Stack](#-technology-stack)
- [System Architecture](#-system-architecture)
- [Installation & Setup](#-installation--setup)
- [Screenshots](#-screenshots)
- [Competitiveness](#-competitiveness)
- [API Documentation](#-api-documentation)
- [Team Members](#-team-members)
- [License](#-license)

---

## 📝 Abstract

MediCare Plus is a full-stack Hospital Management System that digitizes and automates hospital operations, providing a seamless experience for patients, doctors, and administrators. The system addresses critical challenges in healthcare management including appointment scheduling, patient record management, prescription tracking, and inter-departmental coordination.

Built with modern web technologies, the platform offers role-based access control, real-time notifications, AI-powered chatbot assistance, and comprehensive analytics dashboards. The system follows industry best practices for security, scalability, and user experience, making healthcare services more accessible and efficient.

---

## 🎯 Project Description

### Overview

MediCare Plus is a comprehensive healthcare management solution that bridges the gap between patients, healthcare providers, and hospital administration. The system provides a unified platform for:

- **Patient Management:** Complete patient registration, profile management, medical history tracking, and appointment booking
- **Doctor Portal:** Comprehensive dashboard for managing appointments, patient consultations, prescriptions, and availability schedules
- **Administrative Control:** Centralized management of hospital operations including user management, department coordination, analytics, and leave approvals
- **Communication:** Real-time notifications, AI-powered chatbot for instant assistance, and seamless inter-departmental communication

### Core Modules

#### 1️⃣ **Authentication & Authorization**
- Secure JWT-based authentication
- OAuth integration (Google, Facebook)
- Role-based access control (Admin, Doctor, Patient)
- Password reset and email verification
- Session management and security headers

#### 2️⃣ **Patient Portal**
- User-friendly registration and profile management
- Browse and search available doctors by specialty
- Book, reschedule, and cancel appointments
- View medical records and prescription history
- Access lab test results
- AI chatbot for health queries and guidance

#### 3️⃣ **Doctor Dashboard**
- Comprehensive appointment management
- Patient history and medical records access
- Digital prescription creation and management
- Schedule and availability management
- Leave application and tracking
- Patient consultation tracking
- Performance analytics

#### 4️⃣ **Admin Panel**
- System-wide analytics and statistics dashboard
- User management (doctors, patients, staff)
- Department and specialty management
- Lab test configuration and management
- Leave approval workflow
- Appointment oversight and management
- System health monitoring
- Activity logs and audit trails

#### 5️⃣ **Advanced Features**
- **Real-time Notifications:** Socket.io powered instant updates
- **AI Chatbot:** Google Gemini AI integration for health assistance
- **File Upload:** Cloudinary integration for medical documents and images
- **Security:** Helmet.js, rate limiting, XSS protection, SQL injection prevention
- **Email Service:** Automated email notifications via Nodemailer
- **Data Validation:** Comprehensive input validation and sanitization
- **Responsive Design:** Mobile-first approach with Tailwind CSS

### Technical Highlights

- **RESTful API Architecture:** 113+ well-documented API endpoints
- **Database Design:** Efficient MongoDB schema with proper indexing and relationships
- **State Management:** React Context API for global state
- **Security:** Industry-standard security practices including encryption, sanitization, and rate limiting
- **Error Handling:** Comprehensive error handling with custom middleware
- **Code Quality:** Clean, maintainable code following best practices
- **Scalability:** Designed for horizontal scaling and high performance

---

## ✨ Key Features

<table>
  <tr>
    <td>
      <h3>👥 For Patients</h3>
      <ul>
        <li>✅ Easy registration & profile management</li>
        <li>✅ Search doctors by specialty & availability</li>
        <li>✅ Online appointment booking</li>
        <li>✅ View medical records & prescriptions</li>
        <li>✅ Lab test booking & results</li>
        <li>✅ AI-powered health chatbot</li>
        <li>✅ Appointment history & tracking</li>
        <li>✅ Real-time notifications</li>
      </ul>
    </td>
    <td>
      <h3>👨‍⚕️ For Doctors</h3>
      <ul>
        <li>✅ Comprehensive appointment dashboard</li>
        <li>✅ Patient history & medical records</li>
        <li>✅ Digital prescription creation</li>
        <li>✅ Schedule & availability management</li>
        <li>✅ Leave application system</li>
        <li>✅ Patient consultation tracking</li>
        <li>✅ Performance analytics</li>
        <li>✅ Profile & specialization management</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td colspan="2">
      <h3>👑 For Administrators</h3>
      <ul>
        <li>✅ System-wide analytics dashboard</li>
        <li>✅ User management (doctors, patients, staff)</li>
        <li>✅ Department & specialty management</li>
        <li>✅ Lab test configuration</li>
        <li>✅ Leave approval workflow</li>
        <li>✅ Appointment oversight</li>
        <li>✅ System health monitoring</li>
        <li>✅ Activity logs & audit trails</li>
      </ul>
    </td>
  </tr>
</table>

### 🔐 Security Features

- JWT-based authentication with secure token management
- Password hashing using bcryptjs
- Rate limiting to prevent DDoS attacks
- XSS protection and input sanitization
- NoSQL injection prevention
- Helmet.js for security headers
- CORS configuration
- File upload validation

### 🚀 Performance & Scalability

- Optimized database queries with proper indexing
- Lazy loading and code splitting
- Image optimization with Cloudinary CDN
- Efficient state management
- API response caching strategies
- Rate limiting for API protection

---

## 🛠️ Technology Stack

### Frontend

```
⚛️  React 19.1.1          - UI Library
🎨  Tailwind CSS          - Styling Framework
🔄  React Router DOM      - Client-side Routing
📊  Recharts              - Data Visualization
🔥  React Hot Toast       - Notifications
📡  Axios                 - HTTP Client
🎯  Lucide React          - Icon Library
🤖  Google Gemini AI      - Chatbot Integration
🔐  React OAuth Google    - Social Authentication
⚡  Vite                  - Build Tool
```

### Backend

```
🚀  Node.js + Express     - Server Framework
🗄️  MongoDB + Mongoose     - Database & ODM
🔐  JWT + Passport        - Authentication
🔒  Bcryptjs              - Password Hashing
📧  Nodemailer            - Email Service
☁️  Cloudinary            - File Storage
🛡️  Helmet + CORS         - Security
📝  Express Validator     - Input Validation
🤖  Google Generative AI  - AI Integration
🔔  Socket.io             - Real-time Updates
📱  Twilio                - SMS Notifications
⚡  Morgan                - Request Logging
```

### Development Tools

```
🔧  Nodemon               - Development Server
🧪  Jest + Supertest      - Testing Framework
📏  ESLint                - Code Linting
🎨  PostCSS               - CSS Processing
```

---

## 🏗️ System Architecture

```
┌─────────────────────────────────────────────────────────────┐
│                        FRONTEND (React)                      │
│  ┌──────────────┐  ┌──────────────┐  ┌──────────────┐      │
│  │   Patient    │  │    Doctor    │  │    Admin     │      │
│  │    Portal    │  │   Dashboard  │  │    Panel     │      │
│  └──────────────┘  └──────────────┘  └──────────────┘      │
│         │                  │                  │              │
│         └──────────────────┼──────────────────┘              │
│                            ↓                                 │
│                   React Router + Context API                 │
└────────────────────────────┬────────────────────────────────┘
                             │ HTTPS/REST API
                             ↓
┌─────────────────────────────────────────────────────────────┐
│                    BACKEND (Node.js/Express)                 │
│  ┌──────────────────────────────────────────────────────┐   │
│  │              API Layer (113+ Endpoints)              │   │
│  │  • Auth  • Patients  • Doctors  • Appointments       │   │
│  │  • Prescriptions  • Labs  • Notifications  • Admin   │   │
│  └───────────────────────┬──────────────────────────────┘   │
│                          ↓                                   │
│  ┌──────────────────────────────────────────────────────┐   │
│  │              Middleware Layer                        │   │
│  │  • Authentication  • Authorization  • Validation     │   │
│  │  • Error Handling  • Rate Limiting  • File Upload    │   │
│  └───────────────────────┬──────────────────────────────┘   │
│                          ↓                                   │
│  ┌──────────────────────────────────────────────────────┐   │
│  │              Business Logic Layer                    │   │
│  │  • Controllers  • Services  • Utils                  │   │
│  └───────────────────────┬──────────────────────────────┘   │
└──────────────────────────┼──────────────────────────────────┘
                           ↓
┌─────────────────────────────────────────────────────────────┐
│                    DATA LAYER                                │
│  ┌──────────────┐  ┌──────────────┐  ┌──────────────┐      │
│  │   MongoDB    │  │  Cloudinary  │  │ Google AI    │      │
│  │   Database   │  │ File Storage │  │   Chatbot    │      │
│  └──────────────┘  └──────────────┘  └──────────────┘      │
└─────────────────────────────────────────────────────────────┘
```

---

## 🚀 Installation & Setup

### Prerequisites

Before you begin, ensure you have the following installed:
- **Node.js** (v16 or higher) - [Download](https://nodejs.org/)
- **MongoDB** (v6 or higher) - [Download](https://www.mongodb.com/try/download/community) or use [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)
- **npm** or **yarn** package manager
- **Git** for version control

### Step 1: Clone the Repository

```bash
git clone https://github.com/yourusername/medicare-plus.git
cd medicare-plus
```

### Step 2: Backend Setup

#### 2.1 Navigate to Backend Directory

```bash
cd backend
```

#### 2.2 Install Dependencies

```bash
npm install
```

#### 2.3 Configure Environment Variables

Create a `.env` file in the `backend` directory with the following configuration:

```env
# Server Configuration
PORT=5000
NODE_ENV=development
FRONTEND_URL=http://localhost:5173

# Database
MONGODB_URI=mongodb://localhost:27017/medicare-plus
# Or use MongoDB Atlas:
# MONGODB_URI=mongodb+srv://username:password@cluster.mongodb.net/medicare-plus

# JWT Configuration
JWT_SECRET=your_super_secret_jwt_key_here_change_in_production
JWT_EXPIRE=7d

# Google OAuth
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret

# Facebook OAuth
FACEBOOK_APP_ID=your_facebook_app_id
FACEBOOK_APP_SECRET=your_facebook_app_secret

# Cloudinary (File Upload)
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

# Email Configuration (Nodemailer)
EMAIL_HOST=smtp.gmail.com
EMAIL_PORT=587
EMAIL_USER=your_email@gmail.com
EMAIL_PASS=your_app_specific_password

# Google Gemini AI
GEMINI_API_KEY=your_gemini_api_key

# Twilio (Optional - for SMS)
TWILIO_ACCOUNT_SID=your_twilio_account_sid
TWILIO_AUTH_TOKEN=your_twilio_auth_token
TWILIO_PHONE_NUMBER=your_twilio_phone_number
```

#### 2.4 Seed the Database

Create an admin account and initial data:

```bash
npm run seed
```

#### 2.5 Start the Backend Server

```bash
# Development mode with auto-reload
npm run dev

# Production mode
npm start
```

The backend server will start on `http://localhost:5000`

### Step 3: Frontend Setup

#### 3.1 Navigate to Frontend Directory

Open a new terminal window and navigate to the frontend directory:

```bash
cd frontend
```

#### 3.2 Install Dependencies

```bash
npm install
```

#### 3.3 Configure Environment Variables

Create a `.env` file in the `frontend` directory:

```env
VITE_API_URL=http://localhost:5000/api
VITE_GOOGLE_CLIENT_ID=your_google_client_id
```

#### 3.4 Start the Frontend Development Server

```bash
npm run dev
```

The frontend will start on `http://localhost:5173`

### Step 4: Access the Application

Open your browser and navigate to:
```
http://localhost:5173
```

### Default Login Credentials

#### Admin Account
```
Email: admin@medicareplus.com
Password: Admin@123
```

#### Doctor Account
```
Email: dr.rajesh.kumar@hospital.com
Password: Doctor@123
```

#### Patient Account
```
Create a new account via the signup page
```

### 🔧 Additional Commands

#### Backend Commands

```bash
# Run tests
npm test

# Count API endpoints
node count-api-endpoints.js

# Create test patients
node create-realistic-patients.js

# Test all APIs
node test-all-apis.js
```

#### Frontend Commands

```bash
# Build for production
npm run build

# Preview production build
npm run preview

# Run linter
npm run lint
```

### 📦 Production Deployment

#### Backend Deployment (e.g., Heroku, Railway, Render)

1. Set all environment variables in your hosting platform
2. Ensure MongoDB is accessible (use MongoDB Atlas for cloud deployment)
3. Build command: `npm install`
4. Start command: `npm start`

#### Frontend Deployment (e.g., Vercel, Netlify)

1. Build command: `npm run build`
2. Publish directory: `dist`
3. Set environment variables (VITE_API_URL, etc.)

---

## 📸 Screenshots

### 🏠 Landing Page & Authentication
> *Add screenshots of your landing page, login, and signup pages here*

![Landing Page](./screenshots/landing-page.png)
![Login Page](./screenshots/login.png)
![Signup Page](./screenshots/signup.png)

---

### 👤 Patient Portal
> *Add screenshots of patient dashboard, appointment booking, and medical records here*

![Patient Dashboard](./screenshots/patient-dashboard.png)
![Book Appointment](./screenshots/book-appointment.png)
![Find Doctors](./screenshots/find-doctors.png)
![Medical Records](./screenshots/medical-records.png)
![Prescriptions](./screenshots/prescriptions.png)
![AI Chatbot](./screenshots/chatbot.png)

---

### 👨‍⚕️ Doctor Dashboard
> *Add screenshots of doctor dashboard, appointments, and prescription management here*

![Doctor Dashboard](./screenshots/doctor-dashboard.png)
![Doctor Appointments](./screenshots/doctor-appointments.png)
![Patient History](./screenshots/patient-history.png)
![Create Prescription](./screenshots/create-prescription.png)
![Doctor Schedule](./screenshots/doctor-schedule.png)
![My Patients](./screenshots/my-patients.png)

---

### 👑 Admin Panel
> *Add screenshots of admin dashboard, user management, and analytics here*

![Admin Dashboard](./screenshots/admin-dashboard.png)
![System Analytics](./screenshots/admin-analytics.png)
![Manage Users](./screenshots/manage-users.png)
![Manage Doctors](./screenshots/manage-doctors.png)
![Manage Patients](./screenshots/manage-patients.png)
![Manage Departments](./screenshots/manage-departments.png)
![Leave Approvals](./screenshots/leave-approvals.png)

---

> **Note:** To add screenshots, create a `screenshots` folder in the root directory and place your images there. Then uncomment the image tags above.

---

## 🎯 Competitiveness

### Why MediCare Plus Stands Out

#### 1. **Comprehensive Feature Set**
Unlike basic hospital management systems, MediCare Plus offers a complete solution covering all aspects of healthcare management with 113+ API endpoints and extensive functionality.

#### 2. **Modern Technology Stack**
Built with cutting-edge technologies (React 19, Node.js, MongoDB) ensuring high performance, scalability, and maintainability.

#### 3. **User Experience**
- Intuitive, modern UI with Tailwind CSS
- Mobile-responsive design
- Real-time updates and notifications
- Fast loading times and smooth interactions

#### 4. **AI Integration**
- Google Gemini AI-powered chatbot for instant health assistance
- Smart appointment recommendations
- Intelligent data insights

#### 5. **Security First**
- Industry-standard security practices
- JWT authentication with refresh tokens
- Role-based access control
- Data encryption and sanitization
- Rate limiting and DDoS protection

#### 6. **Scalability & Performance**
- Optimized database queries
- Efficient state management
- CDN integration for media files
- Designed for horizontal scaling

#### 7. **Developer Friendly**
- Clean, well-documented code
- Modular architecture
- Comprehensive API documentation
- Easy to extend and customize

### Competitive Advantages

| Feature | MediCare Plus | Traditional Systems | Basic Solutions |
|---------|---------------|---------------------|-----------------|
| **Modern UI/UX** | ✅ React + Tailwind | ❌ Outdated interfaces | ⚠️ Basic HTML |
| **Real-time Updates** | ✅ Socket.io | ❌ Manual refresh | ❌ No real-time |
| **AI Integration** | ✅ Gemini AI | ❌ None | ❌ None |
| **Mobile Responsive** | ✅ Fully responsive | ⚠️ Partial | ❌ Desktop only |
| **API Architecture** | ✅ RESTful (113+) | ⚠️ Limited | ⚠️ Basic |
| **Security** | ✅ Enterprise-grade | ⚠️ Basic | ❌ Minimal |
| **Cloud Integration** | ✅ Cloudinary, OAuth | ❌ Local storage | ❌ None |
| **Analytics** | ✅ Comprehensive | ⚠️ Basic reports | ❌ None |
| **OAuth Support** | ✅ Google, Facebook | ❌ None | ❌ None |
| **Code Quality** | ✅ Clean, documented | ⚠️ Legacy code | ⚠️ Monolithic |

### Market Position

MediCare Plus targets:
- **Small to Medium Healthcare Facilities** - Complete solution at affordable cost
- **Healthcare Startups** - Modern, scalable foundation
- **Educational Institutions** - Comprehensive learning platform
- **Digital Health Initiatives** - Ready-to-deploy system

### Future Roadmap

- 🔮 **Telemedicine Integration** - Video consultations
- 📱 **Mobile Applications** - Native iOS and Android apps
- 🤖 **Advanced AI** - Diagnosis assistance, predictive analytics
- 📊 **Business Intelligence** - Advanced reporting and insights
- 🌐 **Multi-language Support** - Internationalization
- 💳 **Payment Gateway** - Online payment processing
- 📧 **SMS Integration** - Enhanced notifications
- 🔗 **Third-party Integrations** - Insurance, pharmacies, labs

---

## 📚 API Documentation

### Overview

MediCare Plus provides 113+ RESTful API endpoints organized into 14 modules:

#### API Statistics

- **Total Endpoints:** 113
- **GET Requests:** 59 (52.2%)
- **POST Requests:** 23 (20.4%)
- **PATCH Requests:** 15 (13.3%)
- **DELETE Requests:** 9 (8.0%)
- **PUT Requests:** 7 (6.2%)

#### Major API Modules

| Module | Endpoints | Description |
|--------|-----------|-------------|
| 👥 Admin User Management | 18 | Manage users, doctors, patients, leaves |
| 👨‍⚕️ Doctor Dashboard | 15 | Profile, appointments, schedule, prescriptions |
| 🔐 Authentication | 11 | Login, register, OAuth, password reset |
| 👑 Admin Dashboard | 9 | Stats, activity logs, system health |
| 🔔 Notifications | 9 | View, mark read, manage notifications |
| 🧑‍⚕️ Patient Portal | 9 | Profile, dashboard, medical records |
| 👨‍⚕️ Doctor Public Routes | 7 | Search, filter, view doctor profiles |
| 📅 Appointments | 7 | Book, reschedule, cancel appointments |
| 🏢 Admin Departments | 7 | CRUD operations for departments |
| 💊 Prescriptions | 6 | Create, view, verify prescriptions |
| 🌴 Leave Management | 6 | Apply, view, manage leaves |
| 🧪 Lab Tests | 5 | Book, view, manage lab tests |
| 🏥 Departments | 2 | Public department listing |
| 🤖 Chatbot | 2 | AI-powered health assistance |

### Base URL

```
Development: http://localhost:5000/api
Production: https://your-domain.com/api
```

### Authentication

All protected endpoints require a JWT token in the Authorization header:

```
Authorization: Bearer <your_jwt_token>
```

### Sample Endpoints

#### Authentication
```
POST   /api/auth/register          - Register new user
POST   /api/auth/login             - User login
POST   /api/auth/logout            - User logout
GET    /api/auth/me                - Get current user
POST   /api/auth/forgot-password   - Request password reset
PUT    /api/auth/reset-password    - Reset password
```

#### Appointments
```
GET    /api/appointments           - Get user appointments
POST   /api/appointments           - Book appointment
PATCH  /api/appointments/:id       - Update appointment
DELETE /api/appointments/:id       - Cancel appointment
GET    /api/appointments/:id       - Get appointment details
```

#### Doctors
```
GET    /api/doctors                - Get all doctors
GET    /api/doctors/:id            - Get doctor details
GET    /api/doctors/search         - Search doctors
GET    /api/doctors/available      - Get available slots
```

For complete API documentation, see [API_ENDPOINTS_SUMMARY.txt](./backend/API_ENDPOINTS_SUMMARY.txt)

---

## 👥 Team Members

<table>
  <tr>
    <td align="center">
      <img src="https://via.placeholder.com/150" width="150px;" alt="Member 1"/><br />
      <sub><b>Member Name 1</b></sub><br />
      <sub>Roll Number / ID</sub><br />
      <a href="https://github.com/username1">GitHub</a> •
      <a href="https://linkedin.com/in/username1">LinkedIn</a><br />
      <sub>Backend Developer | Database Design</sub>
    </td>
    <td align="center">
      <img src="https://via.placeholder.com/150" width="150px;" alt="Member 2"/><br />
      <sub><b>Member Name 2</b></sub><br />
      <sub>Roll Number / ID</sub><br />
      <a href="https://github.com/username2">GitHub</a> •
      <a href="https://linkedin.com/in/username2">LinkedIn</a><br />
      <sub>Frontend Developer | UI/UX Design</sub>
    </td>
  </tr>
</table>

> **Note:** Update the team member information above with actual names, photos, GitHub profiles, LinkedIn profiles, and roles.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2025 MediCare Plus Team

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 🙏 Acknowledgments

- [React](https://reactjs.org/) - The web framework used
- [Node.js](https://nodejs.org/) - JavaScript runtime
- [MongoDB](https://www.mongodb.com/) - Database
- [Tailwind CSS](https://tailwindcss.com/) - CSS framework
- [Google Gemini AI](https://ai.google.dev/) - AI integration
- [Cloudinary](https://cloudinary.com/) - Media management
- All open-source libraries and tools used in this project

---

## 📞 Contact & Support

For questions, suggestions, or issues, please:

- 📧 Email: support@medicareplus.com
- 🐛 Open an issue: [GitHub Issues](https://github.com/yourusername/medicare-plus/issues)
- 💬 Discussions: [GitHub Discussions](https://github.com/yourusername/medicare-plus/discussions)

---

## ⭐ Show Your Support

If you find this project helpful, please give it a ⭐️ on GitHub!

---

<div align="center">

**Built with ❤️ by the MediCare Plus Team**

![Made with Love](https://img.shields.io/badge/Made%20with-❤️-red?style=for-the-badge)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=for-the-badge)

</div>

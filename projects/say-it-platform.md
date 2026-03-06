# Say It! – English Learning Platform
![Login Screen](../screenshots/logo-sayit.png)
## Overview

Say It! is a web-based academic management platform designed to support the administration of English learning programs and language schools.

The system centralizes academic management processes including students, teachers, academic levels, and course scheduling. It provides role-based dashboards that allow administrators, teachers, and students to interact with the platform according to their responsibilities.

The platform was developed using **Angular** with a modular architecture and integrates **Firebase services** for authentication, data storage, and cloud infrastructure.

Main capabilities include:

• Student registration and management  
• Teacher administration  
• Academic level configuration  
• Academic period management  
• Course and class scheduling  
• Role-based dashboards for administrators, teachers, and students  

<table width="100%">
<tr>

<td width="50%" valign="top">

## Problem

Many small and medium language schools manage their academic operations using spreadsheets, messaging platforms, or manual processes.

This approach creates several operational challenges:

• Lack of centralized academic information  
• Difficulty tracking students and teachers  
• Inefficient scheduling processes  
• Limited visibility of academic periods and course assignments  
• Increased risk of administrative errors  

Without a centralized system, it becomes difficult to scale academic programs or maintain consistent organization across courses and periods.

</td>

<td width="50%" valign="top">

## Solution

Say It! provides a centralized digital platform that manages academic operations through a structured web application.

Administrators can manage the entire academic structure including students, teachers, levels, and periods.

Teachers can access course-related information and student lists, while students can view their academic data through personalized dashboards.

The system was designed with **modularity and scalability**, allowing the application to grow as the academic program expands.

</td>

</tr>
</table>

---

# System Architecture

The platform follows a modular web architecture built with Angular and Firebase services.

Frontend → Angular  
Backend Services → Firebase  
Database → Firestore  
Authentication → Firebase Authentication  
File Storage → Firebase Storage  

The application separates responsibilities across different modules such as administration, student access, teacher dashboards, and shared UI components.

---

# Core Modules

<table>
<tr>

<td width="50%" valign="top">

## ⚙️ Admin Module

Provides administrative control over the academic system.

**Capabilities**

• Student management  
• Teacher management  
• Academic level administration  
• Academic period configuration  
• Employee administration  
• Administrative dashboards  

</td>

<td width="50%" valign="top">

## 👨‍🏫 Teacher Module

Allows teachers to interact with academic information related to their courses.

**Capabilities**

• Teacher dashboard  
• Student list visualization  
• Course-related information access  
• Academic monitoring  

</td>

</tr>

<tr>

<td width="50%" valign="top">

## 🎓 Student Module

Provides students access to their academic information.

**Capabilities**

• Student dashboard  
• Course information access  
• Academic progress visualization  

</td>

<td width="50%" valign="top">

## 🧩 Shared Components

Reusable components used across the platform to maintain UI consistency.

**Includes**

• Navigation bar  
• Sidebar navigation  
• Topbar layout  
• Shared UI elements  
• Global services  

</td>

</tr>
</table>

---

# Firebase Integration

The platform integrates multiple Firebase services to provide backend functionality without the need for a traditional server infrastructure.

Firebase enables real-time data access, authentication management, and scalable cloud storage for the application.

The following Firebase services are used:

• **Firebase Authentication** – Manages user login and role-based access control  
• **Cloud Firestore** – Stores academic data such as students, teachers, levels, and periods  
• **Firebase Storage** – Stores files and media assets used by the platform  

Example Firestore collections used in the system:

• alumnos  
• maestros  
• niveles  
• periodos  
• empleados  

### Example Firestore Structure

![Firestore Structure](../screenshots/sayit-firestore.png)

---

# UI Screenshots

Below are example interfaces from the platform showing different parts of the system.

### Login Interface

![Login Screen](../screenshots/sayit-login.png)

### Admin Dashboard

![Admin Dashboard](../screenshots/sayit-dashboard.png)

### Student Management

![Students Management](../screenshots/sayit-students.png)

### Teacher Dashboard

![Teacher Dashboard](../screenshots/sayit-teacher-dashboard.png)


---

# Future Improvements

Future iterations of the platform could introduce additional features to enhance scalability and academic monitoring capabilities.

Possible improvements include:

• Role-based permission refinement for more granular access control  
• Advanced analytics dashboards for monitoring academic performance  
• Automated course scheduling and class assignment  
• Student progress tracking and academic reporting  
• Notification systems for teachers and students  
• Integration with external learning management systems



# Academia Plus  (E-Learning & Skill Development Platform)

Academia Plus is a full-stack web application built using **native PHP** that functions as an e-learning platform where users can explore, purchase, and learn structured courses based on specific skill domains to improve their career readiness.

The system supports both **learner-side experience (course discovery & purchase)** and **educator/admin-side management (course creation, content delivery, and learning tracking)**.

---

## UI Preview

![Academia Plus Preview](https://raw.githubusercontent.com/MohammadRizqyAkmaluddin/Readme-Assets/main/Academia/asset1.png)

![Academia Plus Preview](https://raw.githubusercontent.com/MohammadRizqyAkmaluddin/Readme-Assets/main/Academia/asset2.png)

![Academia Plus Preview](https://raw.githubusercontent.com/MohammadRizqyAkmaluddin/Readme-Assets/main/Academia/asset3.png)

---

## Key Features

- Course marketplace with categorized learning paths  
- Course purchase and enrollment system  
- User learning dashboard (enrolled courses tracking)  
- Instructor/Admin course management panel  
- Learning progress tracking system  
- Course rating and feedback system  
- Role-based access (Student, Instructor, Admin)  
- Responsive UI for seamless learning experience  

---

## Project Concept

Academia Plus is designed as a **career-focused learning platform**, where users can upgrade their skills through structured, domain-specific courses such as programming, design, and digital skills.

Unlike traditional academic systems, the platform is oriented toward **practical skill acquisition for job readiness and professional growth**, similar to modern e-learning marketplaces.

---

## Tech Stack

- **Backend:** Native PHP (vanilla PHP)  
- **Frontend:** HTML, CSS, JavaScript  
- **UI Framework:** Bootstrap  
- **Database:** MySQL  
- **Architecture:** Custom MVC-inspired structure (no framework)  
- **Deployment:** Apache / Nginx on VPS (optional)  

---

## System Architecture

The application is built with a structured monolithic architecture:

- Separation of logic into controllers, models, and views  
- Reusable UI components for consistent layout  
- Centralized database connection handling  
- Feature-based module organization (courses, users, transactions)  
- Clean routing flow using PHP-based request handling  

---

## Core Modules

- Authentication & Role Management  
- Course Catalog & Category System  
- Course Purchase & Enrollment System  
- Learning Dashboard  
- Instructor Course Management  
- Progress Tracking System  
- Admin Reporting Panel  

---

## Database Design

The database is designed to support scalable e-learning workflows:

- User-to-course enrollment relationships  
- Course categorization (skill-based domains)  
- Transaction records for course purchases  
- Progress tracking per user-course relationship  
- Role-based access control structure  

---

## Installation

```bash
git clone https://github.com/MohammadRizqyAkmaluddin/AcademiaPlus-E-Learning-Platform.git
cd AcademiaPlus-E-Learning-Platform

# import database
# import academia_plus.sql into MySQL

# run locally using XAMPP / Laragon / Apache

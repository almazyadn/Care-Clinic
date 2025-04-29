# 🏥 Care Clinic — Secure Appointment Management System

**Date:** January 2025  
**Tech:** PHP, MySQL, HTML/CSS

---

## 🎯 Overview

Care Clinic is a secure web-based system developed to manage appointments and healthcare interactions between doctors and patients. It features account-based access, appointment booking, secure login, and the ability to manage prescriptions. The system includes essential security features like session handling and password hashing, and provides specialized views for doctors and patients.

---

## 🌟 Key Features

- **User Authentication**: Secure login with password hashing for both doctors and patients.  
- **Role-Based Access Control**: Different pages and actions depending on whether the user is a doctor or a patient.  
- **Appointment Management**: Patients can book, view, and cancel appointments; doctors can manage their schedules.  
- **Specialty Filtering**: Patients can browse doctors by medical specialty using dynamic filtering.  
- **Prescription System**: Doctors can add prescriptions linked to specific appointments and medications.  
- **Session Security**: All pages are protected using session-based authentication.

---

## 🛠 Tools & Technologies

- PHP 8  
- MySQL 8  
- HTML5, CSS3  
- MAMP/XAMPP (for local development)  
- Web hosting platform with FTP & phpMyAdmin access

---

## 📋 Database Overview

The system uses a relational database with the following tables:

- `Doctor`: Contains doctor data like name, email, specialty, image, and hashed password.  
- `Patient`: Holds patient details including name, gender, birthdate, email, and hashed password.  
- `Appointment`: Records all bookings with patient/doctor linkage, date, time, reason, and status (Pending, Confirmed, Done).  
- `Speciality`: Stores the list of medical specialties.  
- `Medication`: Includes a list of medicines used in prescriptions.  
- `Prescription`: Connects medications to appointments for doctors to issue prescriptions.

---

## 📈 Deployment Overview

The system was successfully deployed to an online hosting platform.  
Deployment steps included:

- Uploading all files to the hosting server via FTP.  
- Exporting the local database using phpMyAdmin, then importing it online.  
- Updating database connection credentials in `config.php` to connect with the live server.

---

## 👥 Team

This project was developed by:

- Najla Almazyad  
- Joud Al-Kharashi  
- Dalal Al-Yousef  
- Basmah Al-Rasheed  

Under the supervision of **King Saud University**.

---

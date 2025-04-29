# 🏥 Appointment Management System — Care Clinic

**Date:** January 2025  
**Tech:** PHP, MySQL, HTML/CSS

---

## 🎯 Overview

Care Clinic is a secure web-based system developed to manage appointments and healthcare interactions between doctors and patients.  
It features account-based access, appointment booking, secure login, and the ability to manage prescriptions.  
The system includes essential security features like session handling and password hashing, and provides specialized views for doctors and patients.

---

## 🌟 Key Features

- **User Authentication**: Secure login with password hashing for both doctors and patients.  
- **Role-Based Access Control**: Different pages and actions depending on user type (doctor or patient).  
- **Appointment Management**: Patients can book, view, and cancel appointments; doctors can manage their schedules.  
- **Specialty Filtering**: Patients can browse doctors by specialty using dynamic filtering.  
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

- `Doctor`: Contains doctor data like name, email, specialty, profile image, and hashed password.  
- `Patient`: Holds patient information such as name, gender, birthdate, email, and hashed password.  
- `Appointment`: Records all bookings with patient/doctor linkage, including date, time, reason, and status (Pending, Confirmed, Done).  
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

## 🌐 Demo & Website

- 🔗 **Website Link**: [Add your website link here](#)  
- 🎬 **Demo Video**: [Add your demo video link here](#)

---

## 👥 Team

This project was developed by:

- Najla Almazyad  
- Joud Al-Kharashi  
- Dalal Al-Yousef  
- Basmah Al-Rasheed  

Under the supervision of **King Saud University**.

---

# 🏥 Hospital Management System  
A web-based Hospital Management System built using **PHP, MySQL, HTML, CSS, and JavaScript**.  
It includes complete modules for **patients, doctors, appointments, and authentication** with both frontend and backend logic.

---

## 🚀 Features

### 🔐 Authentication
- User Registration  
- User Login & Logout  
- Session handling  
- Success pages (login + register)

### 👨‍⚕️ Doctors Module
- Add doctor appointments  
- Update appointment  
- Delete appointment  
- Fetch all appointments  
- Fetch a single appointment  

### 🧑‍🤝‍🧑 Patients Module
- Book appointment  
- Update appointment  
- Delete appointment  
- View appointment list  

### 📅 Appointments Management
- CRUD operations  
- Backend API routes  
- Frontend UI for viewing & managing appointments  

### 🖥 Frontend
- Fully responsive UI  
- HTML/CSS/JS-based pages:  
  - index  
  - login  
  - register  
  - appointments  
  - doctors  
  - patients  
  - logout_success  
  - login_success  

---

## 🛠️ Tech Stack

**Frontend:**  
- HTML5  
- CSS3  
- JavaScript  

**Backend:**  
- PHP  
- MySQL (InfinityFree / phpMyAdmin)

**Tools Used:**  
- GitHub  
- InfinityFree Hosting  
- FileZilla (FTP)  

---

## 📂 Folder Structure

hospital-management/
│
├── assets/
│ ├── css/
│ ├── js/
│ └── images/
│
├── Backend/
│ ├── appointment/
│ ├── auth/
│ ├── doctor/
│ ├── patient/
│ └── db.php (Database connection file)
│
└── Frontend/
├── index.html
├── login.html
├── register.html
├── doctors.html
├── patients.html
├── appointments.html
├── login_success.html
└── register_success.html

## ⚙️ Installation & Setup (Local)

1. Install **XAMPP**
2. Move project folder into:
3. Start **Apache** and **MySQL**
4. Open phpMyAdmin → create database
5. Import SQL file (if applicable)
6. Update credentials in `Backend/db.php`

```php
$host = "host_name";
$user = "user_name";
$pass = "password";
$db   = "database_name";

Open in browser:
http://localhost/hospital-management/Frontend/index.html




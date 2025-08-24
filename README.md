# 🎓 College Feedback System

A **web-based College Feedback System** developed using **PHP**, **HTML**, **CSS**, **JavaScript**, and **MySQL**.  
It allows students to provide course and faculty feedback online, and administrators can manage, view, and analyze feedback reports.

---

## ✨ Features

- ✅ **Student Feedback Submission**: Students can submit course/faculty feedback online.
- ✅ **Admin Panel**: Admin can view, filter, and generate reports of feedback.
- ✅ **User Authentication**: Secure login for students and admin.
- ✅ **Responsive UI**: Works on desktops and mobile devices.
- ✅ **Database-Driven**: Stores all feedback securely in a MySQL database.

---

## 🛠️ Tech Stack

| Component     | Details                                  |
|---------------|-------------------------------------------|
| **Frontend**  | HTML5, CSS3, JavaScript                  |
| **Backend**   | PHP                                      |
| **Database**  | MySQL                                    |
| **Icons/UI**  | Font Awesome, basic CSS styling          |

---

## 📂 Project Structure

college-feedback-system/
├── css/ # Stylesheets
├── js/ # JavaScript files
├── images/ # Project images
├── includes/ # Common include files (DB connection, etc.)
│ └── config.php
├── admin/ # Admin dashboard and management files
├── student/ # Student feedback-related files
├── index.php # Entry point or login page
├── feedback_form.php # Feedback submission page
├── report.php # Report generation page
├── logout.php # Logout script
└── README.md # Project documentation

yaml
Copy
Edit

---

## 🚀 Getting Started

### ✅ 1. Clone the Project
git clone https://github.com/onkarvyawahare04-jpg/college-feedback-system.git
cd college-feedback-system
### ✅ 2. Set Up the Database
Launch your MySQL client (e.g., phpMyAdmin or MySQL CLI).

Create a new database, e.g., feedback_system.

Import the provided SQL file (e.g., feedback_form.sql):

sql
Copy
Edit
CREATE DATABASE feedback_system;
USE feedback_system;
SOURCE feedback_form.sql;
### ✅ 3. Configure the Application
Open config.php and update your database credentials:

php
Copy
Edit
define('DB_HOST', 'localhost');
define('DB_USER', 'root');       // Your DB username
define('DB_PASS', '');           // Your DB password
define('DB_NAME', 'feedback_system');
### ✅ 4. Deploy & Run
Place the project folder inside your web server root:

XAMPP → htdocs

WAMP → www

Start Apache and MySQL from your control panel.

Open the application in your browser:

perl
Copy
Edit
http://localhost/college-feedback-system/
Login Options:

Student: Submit feedback form.

Admin: Access the dashboard to view feedback and generate reports.

## ✅ Usage Guide
### Student Flow
Open the feedback submission page.

Fill in the required details and submit.

The system stores your feedback securely in the database.

### Admin Flow
Log in using admin credentials.

Access the dashboard to:

View all feedback.

Filter by course or faculty.

Generate reports (charts, summaries).

## 🔒 Security Best Practices
Use prepared statements in PHP to prevent SQL injection.

Encrypt admin and student passwords using password_hash().

Validate user input both on client-side (JavaScript) and server-side (PHP).

## 📈 Future Enhancements
Add graphical reports using Chart.js or Google Charts.

Implement role-based access control for multiple admin levels.

Add email notifications for admin upon new feedback submission.

Improve UI with Bootstrap or Tailwind CSS.
## 📷 Screenshots
### Student Login
  ![WhatsApp Image 2025-08-24 at 19 10 39_43a464d2](https://github.com/user-attachments/assets/813726cc-0448-4d3b-bf8d-567ca66411d3)
  
### Feedback Form
  ![WhatsApp Image 2025-08-24 at 19 10 40_f28503da](https://github.com/user-attachments/assets/f71f5590-f887-4327-9aa7-b57b28d2ff77)
  
### Admin Login
  ![WhatsApp Image 2025-08-24 at 19 10 40_5b1bca2b](https://github.com/user-attachments/assets/b2d58575-bee6-458e-b79a-4900c7f6f760)

### Admin Dashboard
  ![WhatsApp Image 2025-08-24 at 19 10 43_6ab1f11a](https://github.com/user-attachments/assets/20c8421f-85f8-4f35-bd90-5cc178fac643)

### Feedback Reports & Analytics
  ![WhatsApp Image 2025-08-24 at 19 10 42_3aabcbb7](https://github.com/user-attachments/assets/f8fb3952-33bc-4f85-839b-68d1283a3838)

### Teacher-Course Performance Table
  ![WhatsApp Image 2025-08-24 at 19 10 42_9c18937c](https://github.com/user-attachments/assets/528d29de-310d-4c9c-ba17-9966188a29fe)

## 📬 Contact
- Developer: Onkar Vyawahare
- GitHub: https://github.com/onkarvyawahare04-jpg

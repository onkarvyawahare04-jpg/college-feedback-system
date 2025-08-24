# College Feedback System

A **web-based College Feedback System** developed using **PHP**, **JavaScript**, **HTML/CSS**, and **MySQL**. This platform enables students to provide anonymous feedback on courses and faculty, while administrators can review and analyze the feedback collected.

---

##  Features

- Responsive student **feedback submission** interface.
- **Admin dashboard** for viewing, sorting, and generating reports on feedback entries.
- **Report generation**, potentially including summaries, statistics, or charts.
- **Authentication** for both students and administrators.
- Secure processes to ensure **data privacy** and user validation.

---

##  Technology Stack

| Component     | Details                                  |
|---------------|-------------------------------------------|
| Backend       | PHP (server-side logic, form handling)    |
| Frontend      | HTML5, CSS3, JavaScript                   |
| Database      | MySQL (or compatible, e.g., MariaDB)      |
| Optional      | Charting library (e.g., Chart.js) for reports |

---

##  Project Structure

college-feedback-system/
├── Feedback/ # Scripts for student feedback interface
│ └── ...
├── Report/ # Admin reporting modules
│ └── ...
├── assets/ # CSS, JS, images
│ ├── style.css
│ └── scripts.js
├── includes/ # Shared files (e.g., DB connection)
│ └── connect.php
├── index.php # Landing page or login entry
├── student_feedback.php # Submission handling
├── admin_dashboard.php # Admin overview & analytics
├── config.php # Database configuration constants
└── README.md # Project overview & instructions

---

##  Getting Started

### 1. Clone the Project

```bash
git clone https://github.com/onkarvyawahare04-jpg/college-feedback-system.git
cd college-feedback-system
### 2. Set Up the Database

Launch your MySQL client (e.g., phpMyAdmin or terminal).

Create a new database, e.g., feedback_system.

Import the available SQL file (if any exists in the repository; e.g., feedback_form.sql):

CREATE DATABASE feedback_system;
USE feedback_system;
SOURCE feedback_form.sql;
### 3. Configure the Application

Open config.php and update the database connection details:

define('DB_HOST', 'localhost');
define('DB_USER', 'root');       // Your DB username
define('DB_PASS', '');           // Your DB password
define('DB_NAME', 'feedback_system');

### 4. Deploy & Run

Copy the project folder into your web server's root (htdocs for XAMPP, www for WAMP).

Start Apache and MySQL services.

Visit the app in your browser: http://localhost/college-feedback-system/.

Log in as a student to submit feedback, or as admin to review and generate reports.
## Usage Guide
### Student Flow

Navigate to the feedback submission page.

Complete the feedback form.

Submit; the feedback is stored in the database.

### Admin Flow

Log in via the admin interface.

Browse all submissions, filter by course or faculty.

View generated reports (e.g., pie charts, response summaries).

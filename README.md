# 🗳️ Digital Voting Platform

## 📌 Project Overview

Digital Voting Platform is a full-stack web application designed to conduct elections online in a secure, transparent, and efficient way.
The system allows users to register, login securely, view candidates, and cast their vote digitally. Each registered user is allowed to vote only once, ensuring fairness in the election process.

This project was developed as part of a Computer Science full-stack learning project.

---

## 🚀 Features

• User registration and login authentication
• Secure one-person-one-vote system
• Candidate list display
• Simple and user-friendly voting interface
• Prevention of duplicate voting
• Votes stored securely in database
• Session-based login handling

---

## 🛠️ Tech Stack

Frontend
HTML, CSS, JavaScript 

Backend
php

Database
MySQL 

Server Environment
XAMPP / Localhost

---

## 📥 Installation & Setup

1. Clone the repository

   git clone https://github.com/revathipatnala/Digital-Voting.git

2. Open the project folder in VS Code.

3. Start your local server
   (XAMPP Apache Server).
   

4. Create the database tables in MySQL by checking php files.

5. Configure database connection in the project files.

6. Open in browser:

   http://localhost/Digital-Voting

---

## 🧑‍💻 How to Use the Application

1. Open the website in your browser.
2. Register a new account using the Signup page.
3. Login using your username and password.
4. After login, the system shows the voting dashboard.
5. View the available candidates.
6. Select your preferred candidate.
7. Click Submit Vote.
8. Once voted, the system blocks multiple voting attempts.
9. Logout after completing the voting process.

---

## ⚙️ Working of the Project

The Digital Voting Platform works on a secure authentication-based voting mechanism.

• First, users register and their details are stored in the database.
• During login, credentials are validated with stored database records.
• After successful login, the user is redirected to the voting dashboard.
• The dashboard fetches the candidate list from the database.
• When the user votes, the system records the vote in the database.
• The system checks the voting status and prevents duplicate votes.
• All votes are stored for counting and result processing.

This ensures a transparent and secure online election workflow.

---

## 🔐 Security Features

• Authentication-based login system
• One user can vote only once
• Database vote validation
• Session protection
• Restricted access without login

---

## 🎯 Future Improvements

• Email verification for users
• Admin panel for election management
• Live vote counting dashboard
• OTP-based secure voting
• Deployment on cloud server

---


## 👨‍💻 Author

Your Name
B.Tech Computer  data Science Student
GitHub: https://github.com/revathipatnala

---

⭐ If you like this project, consider giving it a star on GitHub!
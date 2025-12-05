A simple full-stack web application built using Node.js + Express + HTML/CSS/JS for managing student data, attendance, marks, timetable, and student profiles with Admin / Teacher / Student roles.

Features:
1.Role-Based Login

Admin – manage students, attendance, marks, timetable
Teacher – mark attendance, add marks, view profiles, timetable
Student – view profile, attendance %, marks, timetable

2. Student Module (Admin)

Add / Edit / Delete students
Search students
Stores: Roll No, Name, Department, Semester, CGPA, Phone, Parents, DOB
Local photo upload
Export students CSV
🗓 Attendance Module
Mark Present/Absen
Shows attendance summary & percentage
Students can view their own attendance

3. Marks Module

Add marks per subject
Shows marks + grade
Students can view their own marks
Timetable
Admin/Teacher can add class schedule
Students can view timetable

4. Student Profile

Shows all details
Attendance %
Marks + grade
Printable report card

5. Tech Stack

Frontend: HTML, CSS, JavaScript
Backend: Node.js, Express
Storage: JSON files (no database required)

***How to Run***

Install Node.js
Download or clone this repository
In the terminal:

npm install
npm start

Open in browser:

http://localhost:5000

**Project Structure**
project/
│
├── backend/       → server.js + JSON data files
└── src/           → HTML, CSS, JS (frontend)

Online Voting System
An online platform for secure, one-person-one-vote elections. Built using front-end and back-end technologies to manage voter registration, authentication, voting, and result visualization.
#Features
- Voter registration and login
- Candidate management (admin module)
- Real-time vote casting with one-vote-per-user logic
- Vote result calculation and display
- Secure password encryption and database integrity
  
#Technologies Used
- Front-End: HTML, CSS, JavaScript
- Back-End: PHP
- Database: MySQL
- Security: Session validation, password hashing
  
#Folder Structure
online-voting-system/
├── index.html
├── register.html
├── vote.html
├── results.html
├── css/
│   └── style.css
├── js/
│   └── main.js
├── php/
│   ├── db.php
│   ├── login.php
│   ├── register.php
│   ├── vote.php
│   └── results.php
└── sql/
    └── schema.sql
    
#Setup Instructions
- Clone the repo
- Import schema.sql into your MySQL server
- Update DB credentials in db.php
- Run the app on XAMPP/LAMP with a local server
  
#Security Measures
- Encrypted passwords using bcrypt
- Voting restricted to one vote per user
- Session management for protected routes
  
# License
This project is open-source and free to use for academic purposes.



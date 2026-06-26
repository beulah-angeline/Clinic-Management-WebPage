🏥 Clinic Management Web Application
A Java-based web application for managing clinic operations including patient records and appointment handling, built using Java Servlets and JSP with a MySQL backend.


📌 Overview

This clinic management system provides a web interface for managing patient information and clinic workflows. Built as a Java web application with a MySQL database backend, it demonstrates full-stack Java development with CRUD operations and database connectivity.


✨ Features


**Patient Management** — Add, view, and manage patient records
**Appointment Handling **— Schedule and track clinic appointments
**Database Integration** — MySQL backend with structured SQL schema
**Web Interface** — HTML/CSS frontend served via Java Servlets
**SQL Schema Included** — Ready-to-use SQL commands for database setup



🛠️ Tech Stack

LayerTechnologyBackendJava, Servlets (javax.servlet)FrontendHTML5, CSS3DatabaseMySQLServerApache Tomcat


🚀 Getting Started

Prerequisites


Java JDK 8+
Apache Tomcat 9+
MySQL Server
IDE (Eclipse / IntelliJ with Java EE support)


Database Setup

sql-- Run the SQL commands from SQLCommands.sql in your MySQL workbench
source SQLCommands.sql;

Running the App


Import the project into Eclipse or IntelliJ as a Dynamic Web Project
Set up your MySQL connection in the DB config file
Deploy to Apache Tomcat
Open http://localhost:8080/clinic in your browser



📁 Project Structure

Clinic-Management-WebPage/
├── java/com/clinic/        # Java Servlet source files
├── webapp/                 # JSP pages and web assets
│   ├── *.jsp               # Frontend pages
│   └── WEB-INF/            # Web configuration
├── SQLCommands.sql         # Database schema and setup
├── Screenshots/            # App UI screenshots
└── DBTables Screenshots/   # Database table screenshots


📸 Screenshots

(Add your screenshots here from the Screenshots folder)


🗄️ Database Schema

The SQL schema is included in SQLCommands.sql. It sets up all the required tables for patient and appointment management. Run it in MySQL Workbench before starting the application.


🔮 Future Improvements


 Add doctor/staff login and role-based access
 Add appointment reminder notifications
 Migrate to Spring Boot for modern architecture
 Add patient medical history tracking



👩‍💻 Author

Beulah Angeline Yasby J

B.Tech CSE(AI)  · Karunya Institute of Technology and Sciences

📧 beulahangelineyasbyj@gmail.com

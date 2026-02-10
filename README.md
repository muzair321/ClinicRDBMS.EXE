# ClinicRDBMS.EXE
📋 Project Overview<br>
Changez Clinic Management System is a comprehensive desktop application designed<br>
for clinic administration, featuring patient management, visit tracking, inventory<br>
control, and user session logging. Built with Java Swing and SQLite, it provides<br>
a robust solution for small to medium-sized medical practices.<br>
<br>
🛠️ Technology Stack<br>
Backend & Architecture<br>
Java SE - Core programming language<br>
<br>
Maven - Dependency management and project building<br>
<br>
Object-Oriented Programming (OOP) - Clean architecture with proper encapsulation,<br>
inheritance, and polymorphism<br>
<br>
File Handling - For data export/import operations<br>
<br>
Bash Scripting - Automation scripts for deployment and maintenance<br>
<br>
Database<br>
SQLite - Lightweight, file-based database system<br>
<br>
JDBC - Database connectivity and CRUD operations<br>
<br>
Frontend<br>
Java Swing - Desktop GUI framework<br>
<br>
Custom UI Components - Tailored for medical clinic workflow<br>
<br>
Version Control & Deployment<br>
Git & GitHub - Version control and collaboration<br>
<br>
JAR to EXE Conversion - Native Windows executable generation<br>
<br>
Packaging Tools - Creation of distributable application packages<br>
<br>
=> Key Features<br>
🔐 User Session Management<br>
Secure login system with session tracking<br>
<br>
Role-based access control (Admin/Standard)<br>
<br>
Session logging with timestamps<br>
<br>
👥 Patient Management<br>
Complete patient registration with demographics<br>
<br>
Patient search capabilities<br>
<br>
Patient history tracking<br>
<br>
Edit and update patient information<br>
<br>
Bulk patient operations<br>
<br>
🏥 Visit Management & Tracking<br>
<br>
Illness diagnosis recording<br>
<br>
Treatment plans documentation<br>
<br>
Payment tracking and invoicing<br>
<br>
Visit history with detailed timelines<br>
<br>
Prescription management<br>
<br>
📦 Inventory Management System<br>
Medicine and supply tracking<br>
<br>
Multiple storage type support (Bottles, Packets, etc.)<br>
<br>
Inventory categorization<br>
<br>
📊 Logging & Audit Systems<br>
Inventory Change Logs: Complete audit trail of all stock modifications<br>
<br>
User Activity Logs: Track all user actions within the system<br>
<br>
Session Logs: Record all login/logout activities<br>
<br>
Visit Logs: Comprehensive medical visit documentation<br>
<br>
🔍 Search & Reporting<br>
Advanced search across all modules<br>
<br>
Real-time data filtering<br>
<br>
Export functionality for reports<br>
<br>
Dashboard with key metrics<br>
<br>
🗂️ Project Structure<br>
text<br>
src/<br>
├── main/<br>
│   ├── java/<br>
│   │   ├── model/           # Data models (Patient, Visit, Inventory, User)<br>
│   │   ├── db/              # Data Access Objects for database operations<br>
│   │   ├── gui/             # Swing UI components and frames<br>
│   │   ├── security/        # Password hashing etc<br>
│   │   └── app/ Main.java   # Application entry point<br>
│   └── resources/           # Configuration files, images, sounds<br>
├── scripts/                 # Bash scripts for deployment<br>
└── pom.xml                  # Maven configuration<br>
<br>
The .exe is available on the public repo<br>

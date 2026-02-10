# ClinicRDBMS.EXE
📋 Project Overview
Changez Clinic Management System is a comprehensive desktop application designed for clinic administration, featuring patient management, visit tracking, inventory control, and user session logging. Built with Java Swing and SQLite, it provides a robust solution for small to medium-sized medical practices.

🛠️ Technology Stack
Backend & Architecture
Java SE - Core programming language

Maven - Dependency management and project building

Object-Oriented Programming (OOP) - Clean architecture with proper encapsulation, inheritance, and polymorphism

File Handling - For data export/import operations

Bash Scripting - Automation scripts for deployment and maintenance

Database
SQLite - Lightweight, file-based database system

JDBC - Database connectivity and CRUD operations

Frontend
Java Swing - Desktop GUI framework

Custom UI Components - Tailored for medical clinic workflow

Version Control & Deployment
Git & GitHub - Version control and collaboration

JAR to EXE Conversion - Native Windows executable generation

Packaging Tools - Creation of distributable application packages

=> Key Features
🔐 User Session Management
Secure login system with session tracking

Role-based access control (Admin/Standard)

Session logging with timestamps

👥 Patient Management
Complete patient registration with demographics

Patient search capabilities

Patient history tracking

Edit and update patient information

Bulk patient operations

🏥 Visit Management & Tracking

Illness diagnosis recording

Treatment plans documentation

Payment tracking and invoicing

Visit history with detailed timelines

Prescription management

📦 Inventory Management System
Medicine and supply tracking

Multiple storage type support (Bottles, Packets, etc.)

Inventory categorization

📊 Logging & Audit Systems
Inventory Change Logs: Complete audit trail of all stock modifications

User Activity Logs: Track all user actions within the system

Session Logs: Record all login/logout activities

Visit Logs: Comprehensive medical visit documentation

🔍 Search & Reporting
Advanced search across all modules

Real-time data filtering

Export functionality for reports

Dashboard with key metrics

🗂️ Project Structure
text
src/
├── main/
│   ├── java/
│   │   ├── model/           # Data models (Patient, Visit, Inventory, User)
│   │   ├── db/              # Data Access Objects for database operations
│   │   ├── gui/             # Swing UI components and frames
│   │   ├── security/        # Password hashing etc
│   │   └── app/ Main.java   # Application entry point
│   └── resources/           # Configuration files, images, sounds
├── scripts/                 # Bash scripts for deployment
└── pom.xml                  # Maven configuration

The .exe is available on the public repo

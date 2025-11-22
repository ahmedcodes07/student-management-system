README.md
🎓 Student Management System
A comprehensive web-based Student Management System built with Python and Streamlit, featuring a modern interface and full CRUD operations with JSON storage.

🌟 Features
Add New Students with complete information

View All Students in an organized table format

Update Student records and marks

Delete Students with confirmation

Search Functionality to find students quickly

Data Persistence using JSON files

Responsive Design that works on all devices

 Start
Prerequisites
Python 3.8+

Streamlit

Pandas

Installation
bash
# Install required packages
pip install streamlit pandas

# Run the application
streamlit run app.py
Access the Application
Open your browser and navigate to: http://localhost:8501

📱 Interface Overview
Main Features:
Student Form: Add new students with Name, Roll No, and Marks

Student Records: View all students in a clean table format

Statistics Dashboard: See total students, average marks, and highest marks

Action Menu: Easy navigation between different operations

Menu Options:
 Dashboard - System overview and statistics

 Add Student - Add new student records

 View All Students - Browse all student data

 Search Students - Find specific students

 Update Student - Modify existing records

 Delete Student - Remove student entries

 Technical Architecture
Project Structure
text
student-management-system/
├── app.py                 # Main Streamlit application
├── models/
│   └── student.py        # Student data model
├── services/
│   ├── storage_json.py   # JSON data storage handler
│   └── student_manager.py # Business logic and CRUD operations
└── data/
    └── students.json     # Student database
Key Components
Student Class: Data model with validation

StudentManager: Handles all CRUD operations

JSONStorage: Manages data persistence

Streamlit UI: Modern web interface

 Data Management
Student Information:
Name: Student's full name

Roll No: Unique identifier

Performance: Automated grading system

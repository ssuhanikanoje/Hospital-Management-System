# Hospital-Management-System
HospitalManagmentSystem/
│
├── HospitalManagementSystem.java   // Main class
├── Patient.java                    // Patient operations
├── Doctor.java                     // Doctor operations
├── DatabaseConnection.java         // JDBC connection (if separated)
│
└── README.md

🧠 How the System Works
User interacts through a menu-driven console interface
Java backend processes user input
Data is stored and retrieved from MySQL database

Appointment booking checks:
Patient exists
Doctor exists
Doctor availability on selected date

▶️ How to Run the Project
Clone the repository
---> git clone https://github.com/your-username/hospital-management-system.git


Create MySQL database

---->CREATE DATABASE hospital;

Update database credentials in code
String url = "jdbc:mysql://localhost:3306/hospital";
String username = "root";
String password = "your_password";

Run HospitalManagementSystem.java

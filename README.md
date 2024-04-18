
# University Enrollment System

The University Enrollment System is a Java console application designed to manage student enrollments, courses, and faculty assignments within a university setting. It provides functionalities to add students, courses, and faculty members to a database, enroll students in courses, assign faculty to courses, and display available courses.

# Setup Instructions

## Prerequisites
  • Java Development Kit (JDK) installed on your system.
  • MySQL database server installed on your system.

 ## Database 
  1. Start your MySQL database server.
  2. Create a new database named project.
  3. Create the following tables within the project database:
    • students: Columns - student_id (INT, AUTO_INCREMENT), name (VARCHAR), email (VARCHAR)
    • courses: Columns - course_id (INT, AUTO_INCREMENT), course_name (VARCHAR), course_description (VARCHAR), faculty_id (INT)
    • faculty: Columns - faculty_id (INT, AUTO_INCREMENT), name (VARCHAR), email (VARCHAR)
    •  enrollments: Columns - enrollment_id (INT, AUTO_INCREMENT), student_id (INT), course_id (INT), enrollment_date (DATE)
  4. Ensure your MySQL server is running on localhost with the default port 3306, and the username and password are set to the server which has the database.
## Application Setup
  1. Clone this repository to your local machine.
  2. Navigate to the project directory in your terminal or command prompt.
    



# User Guide

## Running the Application
  1. Compile the Java source files using the following command:
```bash
   javac UniversityEnrollmentSystem.java
   ```
  2. Run the compiled Java application using the following command:
```bash
   java UniversityEnrollmentSystem.java
   ```
  
    
# Using the Application
 1. Upon running the application, you will be presented with a menu displaying various options.
  2. Choose an option by entering the corresponding number and pressing Enter.
  3. Follow the prompts to input data as required for each option.
  4. Use the menu option 7 to exit the application.

## Menu Options
  1. Add Student: Add a new student to the database.
  2. Add Course: Add a new course to the database.
  3. Add Faculty: Add a new faculty member to the database.
  4. Enroll Student in Course: Enroll a student in a course.
  5. Assign Faculty to Course: Assign a faculty member to teach a course.
  6. Display All Courses: View a list of all available courses.
  7. Exit: Close the application and exit.

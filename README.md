# STUDENT-MANAGEMENT-SYSTEM

# DESCRIPTION:

**Library Imports and Dependencies:**

The project begins by importing standard Python libraries like: Tkinter for building the graphical user interface (GUI), SQLite for the database backend, CSV for exporting data, and Datetime to handle date-specific operations like attendance logging.

**Database Setup:**

An SQLite database named students.db is created (or connected to if it already exists). Two tables are defined: students: Holds the core student information like name, roll number, email, course, gender, date of birth, attendance count, and grade. attendance_log: Tracks each instance of attendance marking by storing student ID and date.

**Login Screen:**

A simple login screen ensures that only authorized users can access the system. It requires a predefined username and password. Upon successful login, the main application window is launched. Incorrect login credentials trigger an error message.

**Main Application Interface:**

After logging in, the main application window appears. It contains input fields, buttons, and a tabular data view using TreeView. Users can interact with the system to manage student records.

**Add Student Functionality:**

The application allows administrators to enter new student data through form fields. On clicking the "Add Student" button, the input is validated and then stored in the database. The display table updates to reflect the new entry.

**Displaying Student Data:**

All student records are fetched from the database and displayed in a table using the TreeView widget. Each row represents one student with details like ID, name, roll number, and more.

**Attendance Management:**

Users can select a student and increase their attendance count by one with a button click. This also logs the attendance date in a separate table, helping maintain a detailed history.

**Grade Update Feature:**

The admin can update the grade for any selected student by entering a grade in a text field and clicking the “Update Grade” button. The grade is saved to the database and displayed immediately.

**Delete Student Records:**

The system allows deletion of student records. This removes the student’s data from both the student table and the attendance log to keep the database clean and consistent.

**Search Student by Roll Number:**

Users can search for a student using their roll number. If a match is found, only that student's details are shown in the table. This helps in quickly locating individual student data.

**Export to CSV:**

All student data can be exported to a CSV file. The user selects a location to save the file. This feature is useful for backups or analysis in external tools like Excel.

**User Interface Elements:**

The UI is cleanly designed with: Labels and entry boxes for input, Buttons for actions like adding, searching, deleting, and exporting, A TreeView widget for structured data display.

# OUTPUT:

**Login Page:**

![Image](https://github.com/user-attachments/assets/bb733227-48d6-4022-a25c-8becf4ce83d6)

**Add User:**

![Image](https://github.com/user-attachments/assets/0d8d46e6-f993-4701-8e72-e7326e6f910d)
![Image](https://github.com/user-attachments/assets/b349d3af-1753-43a7-95e2-e1cf031d4123)

**Search By RollNumber:**

![Image](https://github.com/user-attachments/assets/2d4304ce-9d56-4a27-9aba-58ae159e1566)

**Show Student Data:**

![Image](https://github.com/user-attachments/assets/30e6612d-74df-42ce-b923-b2105116b003)

**Delete Student:**

![Image](https://github.com/user-attachments/assets/1e6204f3-806a-41f3-8844-d155779a6b02)
![Image](https://github.com/user-attachments/assets/3b7839c3-5033-4137-b88b-7062a72b6ff9)

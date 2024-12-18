Description

This project is a Student Management System designed to perform essential operations such as:

1. Adding new student records.


2. Displaying all student records.


3. Searching for a specific student by ID.


4. Updating student details.


5. Deleting a student record.

     
The program emphasizes clean and modular code, leveraging C++ features like classes, functions, and file I/O.


---

Features

Add New Students: Enter and store details like name, ID, grade, and contact information.

View Records: Display all student details in a structured format.

Search Students: Search for a specific student by ID for quick access.

Update Records: Modify existing student details easily.

Delete Records: Remove a student’s data permanently.

---

Technologies Used

Language: C++

Concepts: OOP (Object-Oriented Programming), File Handling, Data Structures (Arrays), Loops, and Conditional Statements.



---

How to Run the Project

1. Clone the Repository:

git clone https://github.com/yourusername/student-management-system  
cd student-management-system


2. Compile the Code:
Use a C++ compiler like g++ to compile the program:

g++ student_management.cpp -o student_management


3. Run the Executable:

./student_management


4. Follow On-Screen Instructions to add, view, search, update, or delete records.




---

File Structure

student-management-system/  
│-- student_management.cpp  # Main source code  
│-- students.txt            # File for storing student records (created on runtime)  
│-- README.md               # Project documentation


---

Sample Input/Output

Example Menu:

Student Management System  
1. Add Student  
2. View All Students  
3. Search Student  
4. Update Student  
5. Delete Student  
6. Exit  
Enter your choice: 1

Example Input for Adding a Student:

Enter Student ID: 101  
Enter Name: Ali Osman  
Enter Grade: A  
Enter Contact: 612345678  
Record Added Successfully!



---

Future Improvements

Add data validation to handle incorrect inputs.

Implement sorting and filtering options.

Add graphical interface using a library like Qt (optional).



---

Contributors

Farhia Adam Osman





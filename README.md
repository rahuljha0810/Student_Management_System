# Student_Management_System
Introduction to the Student Result Management System project
Plan to modify the project name in the future
Addition of admin section for backend management and security features
Two sections: admin and student, with different permissions and access levels
The project focuses on technologies used: Java(logic, including OOP concepts), Java Swing and Jframe(GUI), and MySQL database.
Java Swing is a part of JFC and is responsible for creating lightweight applications with UI components.
MySQL is used for storing and accessing data.JDBC (Java Database Connectivity) is used for build connection between Netbeans (IDE) and MySQL.
![image](https://github.com/rahuljha0810/Student_Management_System/assets/108356605/1de3a2a8-458f-4a87-b138-103670aafa27)

Use Netbeans IDE for the project's GUI ( palette to add components)to build the project.
Choose Java with Ant as the project type.
Name the project "Student Result Management"
![image](https://github.com/rahuljha0810/Student_Management_System/assets/108356605/ce9cf742-e7c5-4b7a-851b-88e928836c3b)
Add jar dependencies directly through Java with Ant.

The login page will consist of two components: username and password.
The password field will automatically hide the entered text for security.
Add login and back buttons with respective icons.
Store the entered username and password in string variables for further validation.

#AddStudent
We'll be building a new JFrame called admin home.
Importance: It's a crucial frame as we'll integrate MySQL and push data into the database.
Design: Left-hand panel with four buttons, right-hand portion changes based on button click.
Design Part: Panel added on the left-hand side for consistency across frames.
Segregation: JFrame is divided into panels and leftover frames for easier customization.
Buttons: Add student, Add result, Registered students, All students result, Log out.
Design Implementation: Buttons made bold, Add new student button selected with red background.
Functionality: Implementing functionality for add result, registered students, all students result, and log out buttons.
Redirection: Different buttons redirect to respective frames.
![image](https://github.com/rahuljha0810/Student_Management_System/assets/108356605/8c2523e9-c2f9-4ab4-922c-df547d07c802)

The project is a result management portal with an admin and student section
The student Jframe is a simple frame for the roll number and a text field for the user to enter the roll number they want to search for, along with two buttons: search and back.
Upon clicking the search button, the program checks whether the entered roll number is legit or not, meaning it exists in both the student and result tables
The program checks for this by simply checking if the roll number exists in the result table with a call to R.next()
![image](https://github.com/rahuljha0810/Student_Management_System/assets/108356605/ce9baa08-9d0b-40fd-9622-7c1974a349f6)

Final part is JFrame which Show all the Result of the student.
Editiable is not allowed in this JFrame. 
This JFrame provide a beautiful Management of Result and informantion of the Student for which we enterd the roll number.
![image](https://github.com/rahuljha0810/Student_Management_System/assets/108356605/7ca3e00f-fe90-491b-af72-167ef19d478e)

Thank You , Use Net Beans for simplicity.



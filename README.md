 # Student Information GUI

# Description:
This Java Swing GUI application represents a Student Information System. Users can input and display student details, select checkboxes, choose a course, and view the entered information.

# Components:

Main Class (Main.java):

Entry point for the application.
Creates an instance of StudentForm JFrame.
StudentForm Class (StudentForm.java):

JFrame for entering and displaying student information.
Contains panels for different sections.
Form Sections:

Student Details (form1):

Name, Address, City, Province, etc.
Checkboxes (form2):

Student Council and Volunteer Work.
Radio Buttons (form4):

Computer Science or Business.
ComboBox (form10):

Select courses dynamically updated based on radio button.
List of Courses (form5 and form6):

Display selected courses in a JTextArea.
Buttons (form3):

"Display" button shows entered details and selected courses.
Methods:

displayClicked(): Displays student details and selected courses.

courseAdded(): Adds selected courses to the list.

radioClicked(): Updates courses based on the selected radio button.

Usage:

Execute Main.java to launch the GUI.
Fill out details, select checkboxes, choose a radio button, and add courses.
Click "Display" to view entered information and selected courses.

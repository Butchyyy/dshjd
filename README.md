Butch S. Eredillas BSIT 2-A W.M
Student Grade Management System
The Student Grade Management System is a Java application designed to streamline the process of managing student grades. It offers a user-friendly interface with various features to efficiently input, search, update, and delete student records.
The system allows users to enter a student's ID, name, grades, subject, and remarks. The "Add" button saves the entered information, while the "Search" button enables users to search for specific students based on their ID. The "Update" button allows for modifying existing student records, and the "Delete" button removes unwanted records. The "Clear" button resets the input fields for a new entry.
This application aims to improve the organization and accessibility of student grade data, making it easier for teachers and administrators to track student performance and generate reports.

By starting running the application first we need to install the apache netbeans since where using java frame form for our system.
1. Download NetBeans:
•	Go to the official NetBeans website: https://netbeans.apache.org/
•	Click on the "Download" button.
•	Choose the appropriate version and operating system for your computer.
•	Download the installer file.
2. Install NetBeans:
•	Windows:
o	Double-click on the downloaded installer file.
o	Follow the on-screen instructions to complete the installation process.

3. Launch NetBeans:
•	Windows:
o	Go to the Start menu and search for "NetBeans".
o	Click on the NetBeans icon to launch the IDE.
3. Install JDK for Netbeans:
•	Windows:
o	Go to google.com and search the link https://www.oracle.com/java/technologies/downloads/
o	Choose the appropriate bit for your computer.
4. Install connector for connecting the netbeans to the database
   .Heres the provide link for the library https://drive.google.com/drive/folders/1o8s69VaerC7wpvQgXWoaxh0MocugCcif
   .Proceed to the project file in netbeans in click the java project and click library
   .After that, right click the library and click add jar file, find the file and install in the library.
   
After installing all the requirments for netbeans, all you need is to grant all acces and configure the file location of your project .

So in the database, im using myphpadmin.co for easy and free access for my system.
Here's my Credentials
Database name: sql12749875
Username: sql12749875
Password: q6prfFdZhG
Host: sql12.freesqldatabase.com
Port number: 3306

Instruction how the System works:
Setting the Database
Step 1: Go to myphpadmin.co and login
Step 2: Click the structure name and click also the schema.
Step 3: Go to the Upper left and click SQL and hit the button get auto-save query
Procedure how the code works in Java Frame
ADD BUTTON: For the add button, we dont need to input the student id since its we use the function auto incremented for that field. Only we need is to fill up the blank textfield so we can add the new student for our system.
SEARCH BUTTON: For the search button, since we added a new student we can simply hit the button search if we want to see all the student inside the table, but if we need
only to look for specific student we can simply input his/her student id to the textfield and we can see the result.
Update: For the update button, we choose 1 student in the table by clicking his/her student number inside the table, since we will update the current information we need to
fill up new informations for our student, after fill up enter the update button and hit search we can see the present information of the student.
DELETE BUTTON: For the delete button, all we need to do is just type the student number in the textfield and hit the button delete.
Clear BUTTON: For the clear button, The clear button easily work by just clearing all the inputs in the textfields


idk sir how to attach screenshots here about my database structure, so im passing a pdf provinding some screenshots of my work.


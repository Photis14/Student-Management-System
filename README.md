# Student-Management-System
This is a simple Student Management System using Python's `tkinter` for GUI and `sqlite3` for the database. The application provides features to perform basic CRUD (Create, Read, Update, Delete) operations.

## Features:
1. Add a new student with details like:
   - First Name
   - Last Name
   - ID
   - SSN
   - Major
   - Birthdate
   - Address
   - GPA
2. Search a student using the ID.
3. View all student records.
4. Update existing student details.
5. Delete a student record.
6. Reset all input fields.

## Requirements:
- Python 3.x
- Tkinter module: This is a standard GUI library in python and it is installed by default with python installation.
- sqlite3 module: This is also a standard module in python for lightweight database tasks.

## How to Run:
1. Ensure you have `Python 3.x` installed.
2. Clone this repository or download the script.
3. Execute the script using Python:

4. The GUI window will appear, from which you can interact with the application.

## Database Structure:
- The database named `contact.db` is automatically created if it doesn't exist.
- Within the database, a table named `REGISTRATION` is created with the following columns:
- RID: A unique auto-incremented identifier for each record.
- FNAME: First Name of the student.
- LNAME: Last Name of the student.
- ID: A unique identifier for the student.
- SSN: Social Security Number.
- MAJOR: Major subject of the student.
- BIRTHDATE: Date of Birth.
- ADDRESS: Address of the student.
- GPA: Grade Point Average.

## Usage:
- To add a student, fill all the details in the left pane and click the `Submit` button.
- To search for a student, enter the ID in the search bar and click the `Search` button.
- To view all students, click the `View All` button.
- To update student details, select a student record, modify the details, and click the `Update` button.
- To delete a student record, select a student and click the `Delete` button.
- To reset all input fields and refresh the table, click the `Reset` button.

## Warning:
- When deleting a student record, make sure to confirm the prompt to avoid any accidental deletion.
- Ensure you input data in all fields before hitting the `Submit` or `Update` button to avoid any errors.

## Disclaimer:
- This is a basic system and is not meant for any serious or production use.
- It's best to add more advanced features and error handling before using it for larger datasets or a real-world scenario.

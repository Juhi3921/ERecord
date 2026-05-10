# Student Management System

**Technology Used: HTML, CSS, JavaScript**

* We need to make a student management system. This system will use HTML, CSS and JavaScript. It will let users make, read, update and delete student profiles. We will get an array of student objects. Each object has these properties: ID, name, age, grade, degree and email.

* Our job is to make a web page that shows the list of students. It should also let users make, read, update and delete student profiles.. It should let users search for students by name, email or degree.

### Problem Statement

* We need to show the list of students on the page in a way. We will use a table to show all properties for each student. 

* We need to make a form that lets users make student profiles. They can enter the name, age, grade, degree and email. When they click the "add student" button the new student object should be added to the array.

* We need to put an edit icon to each student in the table. When users click this icon they should be able to edit the properties of that student in a form. The form will be the same as the one we use to add students.. When the edit icon is clicked the forms inputs should be filled with the current students information.. The button should change from "add student" to "edit student". When users click this button the student object should be updated with the values.

* We need to put a button next to each student in the list. When users click this button the student profile should be deleted.

* We need to make a search box that lets users filter the list of students by name, email or degree.

* We should use basic DOM manipulation techniques to make all this work. We can use things, like createElement() appendChild() removeChild() and innerHTML. We should not use libraries or advanced JavaScript features like fetch() promises or async/await. We will make the student management system using basic JavaScript.
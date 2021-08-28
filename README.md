# Quiz-Application

Generic Quiz WebApp for Assessment of Students performance. Teachers will be creating courses and adding Quizzes to those courses and similarly, questions to each quiz. Students will be enrolling in the courses using the enrollment key given by the respective course creator. Similarly to attempt the individual quiz student had to select the same enrollment image selected by the teacher at the time of creating the quiz. The quiz will contain multiple types of questions that sometimes need to be corrected by the teacher. so correction of answers and evaluating the marks to the students. 

###### Some Major Incorporations :
* Images will be used for quiz keys. 
* Variety of Question Types can be asked in the quiz.
  * Multiple choice questions
  * Multiple select questions
  * Match the following
  * Fill in the blanks

###### The system comprises 3 major modules.
  * Admin
    1. Add Users ( Teacher , Student )
    1. Manage Users.
  * Teacher
    1. Add Courses
    1. Manage Courses
    1. Add Quizzes
    1. Manage Quizzes
    1. Add Questions
    1. Manage Questions
  * Student
    1. Enroll courses
    1. Enroll quizzes
    1. Attempt quiz
    1. View results

### Tech Stack
* Python ( Flask Framework )
* Sqlite DB
* HTML/Bootstrap/JS

### Note
The project still needed some small changes so you might get many commented code snippets.  
This project works totally fine on all kinds of devices, it was hosted on an EC2 instance of AWS.
* You can check this out here : **http://13.233.88.49/**

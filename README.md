******************************{Steps to run this Application}*********************************

   *======>open mysql workbench 

   *======>creation of database 

   CREATE DATABASE resultdatabase;
   USE resultdatabase;
	
	
   *======>creation of table "teacher"
   
   CREATE TABLE resultdatabase.teacher (
    username VARCHAR(255) PRIMARY KEY,
    password VARCHAR(255),
    role VARCHAR(50)
    );

   
   *=======>creation of table "student"
   
   CREATE TABLE resultdatabase.student 
   ( _id INT AUTO_INCREMENT PRIMARY KEY, 
   roll INT, name VARCHAR(255), 
   dob VARCHAR(255), 
   score INT );


   
   *========>add some sample data to teacher table :-
   
   
    INSERT INTO resultdatabase.teacher (username, password, role)
    VALUES
    ('teacher1', 'password1', 'teacher'),
    ('student1', 'password2', 'student');
	
	  
   
   *========>add some sample data to student table :-
   
   INSERT INTO resultdatabase.student (roll, name, dob, score)
    VALUES
    (101, 'Deepak singh', '1998-05-10', 85),
    (102, 'Jayanti prabha', '1999-02-15', 92),
    (103, 'Aditya verna', '2000-09-20', 78),
    (104, 'Rahul jain', '1997-11-30', 67),
    (105, 'Sajid Ali', '2001-07-08', 95);

  
   
   *to download all packages :-

    npm install

    *to run application use :-
	
    npm start





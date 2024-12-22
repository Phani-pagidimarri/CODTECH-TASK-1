Name : PHANI PAGIDIMARRI

Company : CODTECH IT SOLUTIONS

ID : CT08DS55

Domain : C Prograaming

Duration : Dec to Jan 2025

Mentor : Sravani 

### Overview Of The Project
# Project : Quiz Game development using C 

### Objective
The objective of this project is , "Developing a Quiz Game which Provides Multiple Choice Questons to the user". The aim is to track the users score and provide the fedback based on question. 

## Key Activities 
--**Data Validation** : Checks for unique usernames before saving.
--**Timed Responses** : Uses the time.h library to measure response time for each question.
--**Scoring System** : Updates scores dynamically based on correctness and response time.
--**Memory Management** : Uses an array of up to 50 users, ensuring no overflow.

## Technologies Used 
--**C** : Primary and general-purpose coding language close-to-hardware capabilities.
--**Data Structure** : Struct and arrays
                              --> To represent users, including fields for username and score.
                              --> Storing multiple user accounts (Ac user[50]) and multiple-choice options.
                              
## Explanation
Intially the user need to enter his "UserName" of characters <= 50, before he commence the quiz. At a time only 50 users can participate in the quiz game. 
--> After logging in with the Username , the User can see the below instructions to begin the test.
                                Quiz Game
                            1 - Start The Game
                            2 - Show My Score
                            0 - Exit
--> To start the quiz game , the user need to click " 1 ".
--> After clicking the number " 1 " , the quiz game begins. 
--> And for each question only 60 seconds are allocated , if the user answers te question with the correct option , in less than 60 seconds , his/her answer is validated and the feedback is provided for every question after answering. 
--> For the correct answer , User scores +5 marks and for the wrong answer user scores -5 marks.
--> If the user takes more than the given time , even his/hers answer is correct , the user scores -5 marks. 
After completion of the quiz , User can check their scores by re-entering the same username they given, befoere commencing the test. 
--> After entering the username ,the user need to click the number " 2 " , to view their respective scores. 
The User must click the number " 3 " , in the PC , to exit / quit the test. 

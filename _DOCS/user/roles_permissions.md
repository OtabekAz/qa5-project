stozhka-iryna	Roles and Permissions
strik-anna	Roles and Permissions
sulaiman-shaiakhmedov	Roles and Permissions
tkachenko-lyudmyla	Roles and Permissions
troyeglazov-sergey	Roles and Permissions
uruskiy-ivan	Roles and Permissions
vorobey-roman	Roles and Permissions
volkov-vadim	Roles and Permissions
yulia-liashenko	Roles and Permissions
sakilov-leonid  Roles and Permissions
beylina-polina Roles and Permissions



# Roles and permissions 
## Overview
Every role contains specific set of permissions. 
If a user is assigned with several roles, all permissions 
will be summed up.
 
List of available roles:
* "new"
* "learner"
* "student"
* "teacher"
* "course"
* "quiz"
* "admin"

### New 
Initial role after registration. 
This role Created to protect the app from low-quality profiles.

### Learner: 
 * course: get all ,  
 * lectures: get all, 
 * diary: create  
 * quiz: get, create answer, 
 * flash: get, create training
 
### Student: 
 * course: get all,  
 * lectures: get all, 
 * homework: get all,
 * diary: create  
 * quiz:get, create answer, 
 * flash: get, create training

### Teacher: 
        (have rights: [auth, get all users, get all groups,  lecture (create, update, get), homework(get, create, update), get all diary, quiz(get, create, update, answer)  ]:

### Quiz: 

### Course:
        
### Flash: 

### Admin 
The Admin role has all the permissions available.
Admin's Permissions breakdown by Application and Activities:

* User: auth, get.all, delete.any, update.any;
* Course: get.all, create, update.any, delete,any, lesson.create;
* Group: get.all, get, create, update.any, delete.any;
* Lecture: get.all, get, create, update.any, delete.any;
* Homework: get.all, answer, create, review;
* Diary: get.all, creat, update.any, delete.any;
* Quiz Questions group: get.all, create, update.any, delete.any;
* Quiz question: get.all, create, update.any, delete.any;
* Quiz Answer Group: get.all, create, update.any, delete.any;
* Quiz answer: get.all, create, update.any, delete.any;
* Flashcard group: get.all, create, update.any, delete.any;
* Flashcard Training: get.all, create, update.any, delete.any.

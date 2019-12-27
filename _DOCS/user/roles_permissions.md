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

### 1. New 
Initial role after registration. 
This role Created to protect the app from low-quality profiles.

### 2. Learner: 
 * course: get all ,  
 * lectures: get all, 
 * diary: create  
 * quiz: get, create answer, 
 * flash: get, create training
 
### 3. Student: 
 * course: get all,  
 * lectures: get all, 
 * homework: get all,
 * diary: create  
 * quiz:get, create answer, 
 * flash: get, create training

### 4. Teacher: 
        (have rights: [auth, get all users, get all groups,  lecture (create, update, get), homework(get, create, update), get all diary, quiz(get, create, update, answer)  ]:

### 5. Quiz: 
Any user assigned with the role **‘quiz’** can access, edit, 
delete as well as create new quiz. However, users with the role **‘quiz’** 
cannot change or see their profile settings and info, have no access 
to lectures, courses and any other project section except for _Quiz_ section and _homepage_. 
The role **‘quiz’** can be only assigned to a user by administrator, or assigned 
manually by database administrator.
          
ACL for **‘quiz’** role:
_User:_ auth;
_Quiz question, - answer, - question group, - answer group:_ 
all permissions are granted. (* See Permissions Matrix below)

### 6. Course:
        
### 7. Flash: 

### 8. Admin 
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

stozhka-iryna
strik-anna
sulaiman-shaiakhmedov
tkachenko-lyudmyla
troyeglazov-sergey
uruskiy-ivan
vorobey-roman
volkov-vadim
yulia-liashenko
sakilov-leonid
beylina-polina




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
  * The main task: 
Is in getting account on [https://pasv.us]
to identify a person,to give an access to allowed options. 
  * Steps to create a “new” role:
User have to register on [https://pasv.us/user/register] , and will receive "new" role by default.
All required fields have to be filled to create the account 
After registration, user getting assigned with "new" role.
The ‘new’ role only allows user to edit a person's profile. 
Viewing site materials is not allowed for this role.
After registration, the user receives an email address (confirmation by email).
“new” role can be upgraded to “learner” role only with “admin”.


### 2. Learner: 
 * course: get all ,  
 * lectures: get all, 
 * diary: create  
 * quiz: get, create answer, 
 * flash: get, create training
 
### 3. Student: 

        (have rights: user (auth, get all), course(get all), group(get), lecture (get), homework(get all, answer), diary (get all, create), quiz(get all)
The participants of studying process should get the role “student’. 
After a user is assigned with “student’ role he/she gets access to “Groups” website section in addition to all sections that were accessible for him/her with “learner” role. The list of groups in “Groups” section visible for particular user depends on groups he has access to. 
Every group has specific Access Type, Members and Observers parameters. If the group has “student” Access type, all users with “student” role do see it in the list. If the group has “member” Access type, only students assigned as Members to the group can see it in the list.
Every group has the following sub-pages: Description, Rating, Lectures, Quiz. All these sub-pages are visible for the user with “student” role who has access to the correspondent group. Student account appears on a Rating page only in case he is recorded as a member in Members parameter of a group.
User with “student” role gets access to “Homework” part of a lecture page (route to lectures page: Group -> Lectures - > select the lecture).


### 4. Teacher: 
        (have rights: [auth, get all users, get all groups,  lecture (create, update, get), homework(get, create, update), get all diary, quiz(get, create, update, answer)  ]:
 The role **‘teacher’** can get  all users  in Courses, Groups and their  progress. 
 Also, **‘teacher’** can see all Daily reports in Dairy. 
  This role can get, create, update Lectures, Homeworks and Quizzes.
 * Auth
 * Get all users
 * Courses: get all courses
 * Groups: get all groups
 * Lecture: create, update, get 
 * Homework: create, update, get 
 * Diary: get all
 * Quiz: create, update, get, answer


### 5. Quiz: 
Any user assigned with the role **‘quiz’** can access, edit, 
delete as well as create new quiz. However, users with the role **‘quiz’** 
cannot change or see their profile settings and info, have no access 
to lectures, courses and any other project section except for _Quiz_ section and _homepage_. 
The role **‘quiz’** can be only assigned to a user by administrator, or assigned 
manually by database administrator.
          
ACL for **‘quiz’** role:
* _User:_ auth;
* _Quiz question, - answer, - question group, - answer group:_ 
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




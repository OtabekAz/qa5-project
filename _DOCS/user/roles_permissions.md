# Roles and permissions 

## Overview
Every role contains specific set of permissions. 
If a user is assigned with several roles, all permissions 
will be summed up.
All roles, except for the **"admin"** role, 
can be changed and assigned only by the user with **"admin"** role.
 
### List of available roles:
* "new"
* "learner"
* "student"
* "teacher"
* "course"
* "quiz"
* "flash"
* "admin"

### 1. New 
Initial role after registration. 
This role Created to protect the app from low-quality profiles.
The purpose of this role to impose restrictions on new account before it has been validated.
In order to be assigned with the role **"new"** user have to 
register on [https://pasv.us/user/register] , and will receive role **"new"** by default.
All required fields have to be filled out to create the account.
After registration, user getting assigned with **"new"** role.
The role **"new"** only allows users to access and edit theirs profile information. 
Viewing site materials is not allowed for this role.
After registration, user receives confirmation by email.
The role **“new”** can be upgraded to **“learner”** role only with **“admin”**.

### 2. Learner
 The role 'learner' has restricted permissions and rights:
  * course: get all ,  
  * lectures: get all, 
  * diary: create  
  * quiz: get, create answer, 
  * flash: get, create training
  
 Learner has access to all courses, included lectures, tests, cards, conspects and quizes.
 This role enable to create diary post, but unable edit that after publishing. 
 While get training through quiz learner can create answers. 
 Learner can create, edit and use flash cards.
 
### 3. Student
The participants of studying process should get the role “student’. 
After a user is assigned with “student’ role he/she gets access to “Groups” website 
section in addition to all sections that were accessible for him/her with “learner” role. 
The list of groups in “Groups” section visible for particular user depends on groups 
he has access to. 
Every group has specific Access Type, Members and Observers parameters. 
If the group has “student” Access type, all users with “student” role do see it in the list. 
If the group has “member” Access type, only students assigned as Members to the group 
can see it in the list.
Every group has the following sub-pages: Description, Rating, Lectures, Quiz. 
All these sub-pages are visible for the user with “student” role who has access 
to the correspondent group. Student account appears on a Rating page only in case 
he is recorded as a member in Members parameter of a group.
User with “student” role gets access to “Homework” part of a lecture page 
(route to lectures page: Group -> Lectures - > select the lecture).

### 4. Teacher
 The role **‘teacher’** can access users list in Courses, Groups and their progress. 
 Also, **‘teacher’** can see all Daily reports in Dairy. 
 This role can access, create, update Lectures, Homeworks and Quizzes.
 * Auth
 * Get all users
 * Courses: get all courses
 * Groups: get all groups
 * Lecture: create, update, get 
 * Homework: create, update, get 
 * Diary: get all
 * Quiz: create, update, get, answer

### 5. Quiz
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

### 6. Course
        Any user with the "Course" role has access to the title 
        project page "Progress Monitor" and section "Course". 
        In the Courses section, with the role of the “Course”, 
        it is allowed to register, create and edit the content 
        of courses and lessons. 
        Group courses by name and sections, additions to courses, 
        links to lectures from YouTube, links to additional 
        material for studying the topic of  the lesson. It is 
        also possible to tracking student progress and update it. 
        acl: ["course.get.all", "course.create", 
        "course.update.any", "lesson.create"]

### 7. Flash

### 8. Admin 
The **"admin"** role has all the permissions available.
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

### Prepared by:
* Stozhka-iryna
* Strik-anna
* Sulaiman-shaiakhmedov
* Tkachenko-lyudmyla
* Troyeglazov-sergey
* Uruskiy-ivan
* Vorobey-roman
* Volkov-vadim
* Yulia-liashenko
* Sakilov-leonid
* Beylina-polina




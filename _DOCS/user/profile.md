##**Profile page**
###**1. Description of Profile page**

1.1. Profile page is displayed after User clicks `Login` button on homepage.
Then User should be redirected to url: https://app.pasv.us/user/.
Profile page is a display or a summary of User account.

There are Menu bar with 5 fields (hyperlinks):
* **Progress Monitor:** after clicking on it User goes to the homepage.

* **Courses:** after clicking on it User goes to https://app.pasv.us/course.
Here User can find available for him/her list of courses.

* **Cards:** after clicking on it User goes to https://app.pasv.us/flash.
Here User can find list of FlashCards.

* **Groups:** after clicking on it User goes to https://app.pasv.us/group.
Here User can find the list of all available lectures divided by topic.

* **Diary:** after clicking on it User goes to https://app.pasv.us/diary.
On this page User can create his/her daily report and
see daily reports of other members of group.

1.2. Profile page also contains a field (hyperlink) with User name.
After clicking on it dropdown list pops-up.

There are 3 options:

* **Profile:** this field is active but it does not redirect User anywhere.
So he/she stays on the same page.

* **Settings:** this field redirects User to https://app.pasv.us/user/edit/
Here he/she can edit his/her Profile.

* **Logout:** by clicking on it User can log out.


1.3. On Profile page User can also see small icons and labels. 
Icon is available if User indicated link to the website during registration.

* **Google Docs icon:** it redirects User to his/her Google Document.

* **Facebook icon:** it redirects User to his/her Facebook account.

* **LinkedIn icon:** it redirects User to his/her LinkedIn account.

* **GitHub icon:** it redirects User to his/her GitHub account.

* **Codewars icon:** it redirects User to his/her Codewars account.

* **Slack icon:** it redirects User to his/her Slack account.

* The label (for example **QA5**) shows the name of the group in which User is studying.

* This label shows **User role**. It can be new, learner, student, teacher, admin etc.
___

###**2. Description of Codewars elements**
Description is made for the student role:

* **Coin:** the numbers to the right of the coin indicate the user's progress.

* **Rank:** shows the level of user development depending on the tasks (hereinafter - katas) being solved on Codewars.

* **Honor:** shows the number of points assigned to the user depending on the tasks performed on Codewars.

* **Task Completed:** shows the number of tasks performed in Codewars (including repeating decisions).

* The **graph** shows the progress of the user depending on the Honor and the Completed task in time, expressed in days of the month.
___

###**3. About**
* Field "About" shows information of User’s experience, skills, hobbies.
Information can appears in the user’s preferred language.

**Example:**
IT specialist with 7+ years of professional experience in information security.
I have a variety of hobbies. I hike with my dog every chance I get... I spend time with my spouse and children...
___

###**4. Goals**
User is asked to tell about his goals in programming and career. 
Text area is required.
The default state is zero character and the placeholder is  "1… 2… 3… ".
___

###**5. Completed challenges**
**5.1. Purpose of the field:**
* **`Completed Challenges`** is a profile page field which main idea is to show a list of User completed tasks in Codewars.

* An example of a proper title is: **`Completed Challenges 258`**, where **`258`** means a quantity of solved katas.

**5.2. Button `Update list`:**
* It refreshes the list of solved katas.

**5.3. List of solved katas**
* List has to include a table with two columns. Columns have no headers. Each line describes one certain kata:
  * First column contains date and time when the kata was solved.
  * Second column contains the name of solved kata which has to be a hyperlink leading to this kata at codewars.

* List has to display all solved katas and has to be sorted by solved date.
* The whole list has to be displayed at one web page.
* An example of list:

|     |     |
| --- | --- |
| **12.25.19**  _12:35_ | [String incrementer](https://www.codewars.com/kata//54a91a4883a7de5d7800009c) |
| **12.25.19**  _09:59_ | [Human Readable Time](https://www.codewars.com/kata//52685f7382004e774f0001f7) |
| **12.21.19**  _11:20_ | [Snail](https://www.codewars.com/kata//521c2db8ddc89b9b7a0000c1) |
| **11.11.19**  _21:15_ | [Multiply](https://www.codewars.com/kata//50654ddff44f800200000004) |


###**6. Daily reports**
**6.1. Description of Daily reports:**

One of the obligatory parts for Student role is creating **Daily reports**.
After Daily report was created by User (using `Create day report` button on https://app.pasv.us/user/),
it appears on the list of all User’s Daily reports.
Label Daily reports is located on the top of Daily reports section.
On the right from Daily report there is a label icon with quantity of Daily reports current User has created.

**6.2. Structure:**

New Daily reports are added to the top of the list of previous reports;
Each Daily report on the list has a line that shows the date of creation (Month, Day, Year and Time);
Under the date labels with names of dropdown fields that User chose while creating Daily report are displayed.
Then actual text of Daily report is shown.
There is Like icon that shows how many likes this report has (from other Users). User can Like his own report.
User’s report can be approved by Admin or other person with the same privilege.
___

###**7. Footer:**
* Footer field contains version number, copyright notice with year and application slogan “eat(); sleep(); code(); repeat();”

**Example:**
Version 0.1.109
© 2019 eat(); sleep(); code(); repeat();
___
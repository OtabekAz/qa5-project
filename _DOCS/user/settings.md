pe-liudmila	Settings
sardari-aya	Settings
semenovich-vladimir	Settings
seryakov-andrey	Settings
sharygin-aleksei	Settings
shchekina-olga	Settings
silchuk-nazariy	Settings
skliarova-ekaterina	Settings
smoljaninov-pavel	Settings
#### Introduction (General description) - Liudmila Pe
The page "Settings" allows the user to change their personal information including first and last names, 
cell phone number, "about" information, update their personal goals, English level, 
links to social media pages and other information. 
Registration page is displayed after the user clicks “Settings” in the dropdown menu under their name on the Homepage.
 The user should be redirected to “Edit profile” page, url: https://app.pasv.us/user/edit/...
 
#### Header/Footer -  Aygul Sardari
Setting Page always displays Header and Footer.  
 * Header is displayed Navigator bar:
Clickin on the” Progress monitor”  gets redirected user  to the Home Page.
Clicking on the “Courses” gets redirected user  to the “Courses” Page.
Clicking on the “Cards” gets redirected user  to the “FleshCards” Page.
Clicking on the “Groups” gets redirected user  to the “Groups”  Page.
Clicking on the “Diary” gets redirected user  to the  “Daily reports” Page.
Clicking on the Application name opens the drop down menu: 
Selecting “Profile” option in the dropdown gets redirected user  to the “Daily reports” Page with personal achievements. 
Selecting “Setting” option in the dropdown gets redirected back to the “Setting” Page. 
Selecting “Logout” option in the dropdown gets log out from apps and redirected user  to the “User Login” Page. 
 * Footer is displayed two lines according to spec requirements.
First line is Version: {version}”, {version} = current version (verify with devs that version is up-to-date)
Second line (current year, JavaScript style’s slogan): © 2019 eat(); sleep(); code(); repeat();

#### First Name/Last Name - Vladimir Semenovich
#### Email confirmed  -  Andrey Seryakov
#### Cell phone number - Aleksei Sharygin

Cell phone number is a required field. Field has a validator:
   * Phone number should start from country code. 
   * Phone number length should be 11-13 numbers. 
   * Only numbers can be used.
   * If user used wrong symbols or wrote the wrong number of symbols application should show the message to help user understand the problem.

#### About/Goals/English level - Olga Shchekina
# ABOUT
About is a required field.
The user should write information about himself, his experience, hobby. Any language can be used. 

# MY GOALS
My Goals  is a required field.
The user should write information about his goals in programming, career. Any language can be used. 

# ENGLISH LEVEL
User must select one of the English language levels from the pop-up menu: 
Zero, Beginner, Elementary, Pre-intermediate, Intermediate, Upper-intermediate, Advanced, Proficient, Native.

#### Google Doc resume link/LinkedIn profile link/
#### Facebook profile link/GitHub profile link - Nazariy Silchuk
#### T-shirt size/Delivery address - Pavel S.

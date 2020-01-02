## User Login
___
### Description
* To be able to login, user must be already registered to the web-page app.pasv.us.
* User Login page https://app.pasv.us/user/login is displayed after user clicks "Login" button on the homepage.

### User Interface

#### Header
* Hyperlink __“Progress Monitor”__ returns to homepage app.pasv.us. 
* Buttons: Login, Register.

#### Body
 * User has to fill 2 required text fields: email and password. 
 * These fields should correspond user’s email and password while their registration.

* __Email__ - input field, required, accepts only existing on the database user’s email.

* __Password__ - input field, required, masked by dots.

* __Login__ button - in case of valid credentials, user is redirected to the user’s profile page. In case of invalid credentials, the error message appears.

*  __Forgot Password?__ redirects user to URL https://app.pasv.us/user/password/reset/request. 

#### Footer
* Footer contains version number, copyright notice with year and application slogan “eat(); sleep(); code(); repeat();”
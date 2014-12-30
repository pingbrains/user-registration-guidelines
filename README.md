User Registration Guidelines
============================

You can refer to below guidelines while coding user registration / SignUp module for any project.

* <b>Email</b>
  * Max length for email should be aroute 254 characters.
  * All Email addresses should be case insensitive.
  * Validate that email address is unique in a given DB table.
* <b>Usernames:</b>
  * Usernames can contain letters (a-z), numbers (0-9), underscores (_). [Optionally, if you want you can also allow dashes (-), apostrophes ('), and periods (.)]
  * Usernames must begin with a alphabet. Username can end with either letter or number or underscore.
  * All Usernames should be case insensitive
  * Validate that username is unique in a given DB table.
  * Username should be atleast 4 alphanumeric chracters. 
* <b>First Name & Last Name</b>
  * Max length for first name and last name should be 60 characters. First and last names should support unicode/UTF-8
* <b>Password:</b>
  * If you are using Laravel framework then datatype for password field should be CHAR(64). Otherwise you can set it to varchar(255)
  * Password should be between 6 to 20 characters.
  * Password MUST include at least 1 UPPERCASE alphabetic character, 1 LOWERCASE alphabetic character and 1 numeric character. 

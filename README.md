# Chat App - Part 1
## Student information
Khanyani Mnwana
ST10489373
PROG5121
------------------------
## Project Information
The Chat App is divided into 3 files
### The first one is Login.java
this class handles the validation and credentials storage with has the following methods:
checkUsername(String username) - which will return true if the username contains an underscore and is less than 5 characters
checkPasswordComplexity(String password) - this will return true is the password is more than 8 characters, has a capital letter, number and special character.
checkCellPhoneNumber(String phone) - will return true is the number starts with +27 and is exactly 12 characters long
registerUser(Sting username, String password, String phoneNumber) - runs and checks all and stores the credentails if valid
loginUser(String username, String password) - compares them with credentials stored and returns true if the credentials match
returnLoginStatus(boolean success) - this returns a welcome message on succeesfull login or an error message on unsuccessfull login
--------------------------
### MainApp
i added a scanner that will allow the user to enter their information - Scanner input = mew Scanner(System.in);
a method that will create an objrct of the login class - Login login = new Login();
#### Registration section
this is where the user will be required to register, by entering a username, password nd cellphone number,if the user registers successfully a " user registered successfully message response will show if not a " registration failed" response will show following with " please try again"
#### Login section
this section is for when the user is done registering
the user needs to enter their registration credentials
it will give the user 5 login attempts to enter the correct credentials
if all attempts have been used up, the user account will be locked 
---------------------------
### LoginTest
a test class that will run a series of inputs through the login methods and prints the results to the console:
this will test the user registration and the login registration.


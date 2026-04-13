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

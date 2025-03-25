# email-password-generator
email+password generator


Description:

This C# code generates random email addresses and passwords based on a given number. It uses a cryptographically secure random number generator to generate strong passwords and email addresses.

How to use:

Compile the code using a C# compiler.
Run the executable.
Enter the desired number of email addresses and passwords to generate and press Enter.
The generated email addresses and passwords will be included in the console.
Functionality:

Generates random email addresses with the domain "@gmail.com".
Generates random passwords that include letters, numbers, and special characters.
Uses RandomNumberGenerator to ensure cryptographic security of the generated passwords.
Outputs the generated email addresses and passwords to the console.
Example:

If the user enters 3, the program will output:

Email 1: ...@gmail.com
Password 1: ...
Email 2: ...@gmail.com
Password 2: ...
Email 3: ...@gmail.com
Password 3: ...
Dependencies:

System
System.Collections.Generic
System.Text
System.Security.Cryptography
Notes:

The lengths and character sets for generating email addresses and passwords can be customized by changing the emailChars and passwordChars constants.
This code is for demonstration purposes and should not be used to generate passwords for your own accounts.

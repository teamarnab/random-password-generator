#Random Password Generator

Problem Statement
1. This program will generate a random password which is either a combination of alphabets or a combination
of alphabets and numbers or alphabets, numbers and special characters.
2. User should be able to choose how long they want their password but it has to be between 7 characters 
and 15 characters in length.
3. User can choose if the password should be 'not so strong', 'mildly strong' or 'strong'.
4. User can generate as many random passwords they want without having to re-run the program.
5. For every invalid input user will get a error message and a chance to re-enter their choice.


Steps Followed
1. import python's random library
2. Create 3 lists. One of all English alphabets, one of numbers from 0-9 and one of special characters.
3. Created a function that would accept one argument and based on it combine the three of the above lists accordingly.
4. A while loop to enable user to generate random password as many times as they want.
5. Asking for length of the Password.
6. Asking for password strength.
7. Creating the correct combination of list/s as required by user.
8. Creating an empty variable to fill with characters one by one.
9. using a for loop to iterate and fill the empty variable with one character until required length is achieved.
10. Printing the result and asking the use again if they want to generate another password. 

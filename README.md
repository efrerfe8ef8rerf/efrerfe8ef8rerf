Create a program that checks if inputs have a valid command and string and translates it. You will receive n count of strings. For each string, check if it's valid.
A string is valid when:
•	The command is surrounded by "!", starts with an uppercase letter, followed only by lowercase letters.
•	The command Is minimum 3 characters long
•	There is a colon after the command.
•	There is a string consisting of alphabetical letters between square brackets "[" and "]".
•	It must be minimum 8 characters long.
Example for a valid string: 
"!Send!:[IvanisHere]"
You must check if the string is valid and if it is - translates it. If it isn't - print the following message: 
"The message is invalid"
Translating a string means taking all letters from the string and turn them into ASCII numbers. After successful translation, print it in the following format:
"{command}:{number1} {number2} … {numberN}"
Note: Translate only the text in the string. If you have "[Ivan is Here]", the part that you need to translate is "Ivan is Here". 
Input
•	On the first line, you will receive an integer n - the count of inputs.
•	On the next n lines - input that you must check if it has a valid string.
Output
•	Print the result in format described above.
in pyhthono

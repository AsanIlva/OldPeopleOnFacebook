# Psuedocode

1. Ask for the length of the password
   prompt function, save to a variable
   check if value is valid( between 8 - 128) if else statement

2. sk for lower, upper, numbers, symbols
   confirm function - returns true or false
   var includeUpper = confirm("message");
   repeat for other char types

3. Check if user aswers no to all questions
   if statement to check that at least 1 value is true

4. var uppercase = ["A","B"...."Z"];
   var lower = ["a","b"...."z"];
   numbers and symbols

5. var availableCharacters = []

6. check if user wants uppers, if so, add uppers to availableCharacters array
   check if user wants lowers, if so, add lowers to availableCharacters array
   etc
   to join two arrays, concat()

7. availableCharacters = ["A","B"... "1","2"]

8. var password = ""

9. for loop, starting at 0, ending at password length
   inside the for loop
   select a character out of the array.
   Add it to the password (use the += operator to add a character to a string)
   snippet to generate a random index in an array:
   Math.floor(Math.random() \* availableCharacters.length)

10. Check that there is at least one value of each selected type in the password, if not, generate again.

11. return the password value.

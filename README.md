# Practice JS String Processing Problems
## Course 210: Computational Thinking and Javascript Programming
## Dave Pinchevski --- Launch School

Strings
Create a variable named firstName and set it equal to your first name. Set another variable named lastName to your last name. Join the two together, separated by a space, and store the result in a variable named fullName. Log the value of fullName.


Call concat on firstName using lastName as an argument. Log the return value.


Split the fullName variable into an array that contains the first and last names as separate strings. Log the value of the array.


Create a variable named language and set it equal to 'JavaScript'. Find the index of the first occurrence of the letter 'S' and save it to a variable named idx variable. Log the value of idx.


Call charCodeAt on the language variable with an argument of idx. Save the return value to a variable named charCode, then log the value of charCode.


Log the return value of String.fromCharCode when you pass it charCode as an argument.


Find the index of the last occurrence of the letter 'a' in the language variable and log the result.


Create two variables, a = 'a' and b = 'b'. Log a "greater than" comparison between the two variables. Reassign the value 'B' to variable b, then compare the two variables again, and log the comparison value.


Create variables aIndex and vIndex and store the index of the first occurrences of letters 'a' and 'v' in the language string. Call the substr method on language with aIndex as the first argument, and 4 as the second argument, e.g., language.substr(aIndex, 4). Log the return value. Repeat the operation using vIndex as the first argument.


Repeat the previous problem, but this time use substring instead of substr. Note how the results differ because of the different ways these methods interpret the second argument:


Create variables named fact1 and fact2 and set them equal to 'JavaScript is fun' and 'Kids like it too', respectively. Combine the values of the two variables with the string ' and ' between them, and store the result in a variable named compoundSentence. Make sure the first letter of fact2 shows up as lowercase in compoundSentence. Log the value of compoundSentence.


Log the first letter of fact1 and fact2 using bracket notation.


Create a variable named pi and set it to the result of 22 / 7. Convert pi to a String using the toString method. Search the resulting string for the final occurrence of '14', and log its index position.


Create a variable named boxNumber and set it to the result of 356.toString(), and log the result. Before moving on, try to run your program.


One way to avoid this is to use two periods instead of one. Replace 356.toString() with 356..toString(), and try running it again.


Some "linter" programs reject this usage, and instead suggest that you use parentheses. Update your program again: eliminate the second period, and place 356 in parentheses, then run the program again.


Convert the boxNumber variable back to a number using parseInt. To make sure the result is a number, you can log typeof boxNumber to verify the type of the result. Now convert the number back to a String by using the String() function and log the typeof of the result to verify it is now a String.


Write a program that asks for a user's name, then greets the user with that name. If the user appends a ! to his name (e.g., 'Bill!'), the computer should "yell" its greeting: that is, it should log everything to the console in uppercase. You can check whether the name ends with a ! using String.prototype.endsWith() (ES6 only). You can remove the ! from the user's name with String.prototype.slice().

Examples

What is your name? Bob
Hello Bob.                                   // console output


What is your name? Bob!
HELLO BOB. WHY ARE WE SCREAMING?             // console output

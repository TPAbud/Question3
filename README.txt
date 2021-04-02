File "Question3.txt" contains the code developed to solve question 3.

When the code starts, it asks the user to type parameters 's','t' and 'k', via input interface.
The user must press 'enter' after typing each parameter.

Uppercase letters in strings 's' and 't' are automatically converted to lowercase ones.
Spaces in strings 's' and 't' are deleted.
If the user types characters other than letters of Portuguese alphabet for strings 's' and 't', function 'ConcatRemove' ends.
If the length of strings 's' or 't' exceeds the range from 1 to 100, function 'ConcatRemove' ends.
If the value of parameter 'k' exceeds the range from 1 to 100, function 'ConcatRemove' ends.

If it is possible to get string 't' by executing exactly 'k' operations on the string 's', then 'ConcatRemove' prints 'Yes' and the number of concatenations and exclusions.
Otherwise, it simply prints 'No'.

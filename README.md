# Strings-and-array
THEORY

Array

An array in C or C++ is a collection of items stored at contiguous memory locations and elements can be accessed randomly using indices of an array. They are used to store similar types of elements as in the data type must be the same for all elements. They can be used to store the collection of primitive data types such as int, float, double, char, etc of any particular type. To add to it, an array in C or C++ can store derived data types such as the structures, pointers, etc.
There are two types of arrays:

One Dimensional Array
Multi Dimensional Array

One Dimensional Array: A one dimensional array is a collection of same data types. 1-D array is declared as:

data_type variable_name[size]

data_type is the type of array, like int, float, char, etc.
variable_name is the name of the array.
size is the length of the array which is fixed.

MultiDimensional Array: A multidimensional array is also known as array of arrays. Generally, we use a two-dimensional array. It is also known as the matrix. We use two indices to traverse the rows and columns of the 2D array. It is declared as:

data_type variable_name[N][M]

data_type is the type of array, like int, float, char, etc.
variable_name is the name of the array.
N is the number of rows.
M is the number of columns.

Strings

C++ string class internally uses character array to store character but all memory management, allocation, and null termination are handled by string class itself that is why it is easy to use

The string data_type in C++ provides various functionality of string manipulation. They are:

strcpy(): It is used to copy characters from one string to another string.

strcat(): It is used to add the two given strings.

strlen(): It is used to find the length of the given string.

strcmp(): It is used to compare the two given string.

ALGORITHM:

String Display

Start

Declare a string variable to store the input string (inputString).

Get the input string (inputString) from the user or from any source.

Use a for loop to iterate through the characters of the string:

Initialize a loop variable (i) to 0.

Continue the loop as long as i is less than the length of the string (inputString.length()).

In each iteration of the loop, print the character at index i.

Increment i after printing each character.

End


String Length

Start

Declare a string variable to store the input string (inputString).

Get the input string (inputString) from the user or from any source.

Initialize a variable (length) to 0. This variable will be used to count the characters in the string.

Use a for loop to iterate through the characters of the string:

Initialize a loop variable (i) to 0.

Continue the loop as long as the character at index i is not the null character ('\0').

In each iteration of the loop, increment the length variable by 1.

Increment i to move to the next character.

After the loop completes, the length variable will contain the length of the string.

Display or use the length as needed.

End


String Concatenation and Reverse String Concatenation

Concatenation Algorithm:

Start

Declare two string variables, str1 and str2, to store the input strings.

Get input for str1 and str2 from the user or from any source.

Declare a string variable, resultStr, to store the concatenated string.

Use a for loop to concatenate str1 and str2:

Initialize a loop variable (i) to 0.

Iterate through the characters of str1 using i and append each character to resultStr.

Repeat the above step for str2.

Display or use resultStr as needed.

End


Reverse Concatenation Algorithm:

Start

Declare a string variable, concatenatedStr, to store the concatenated string.

Get input for concatenatedStr from the user or from any source.

Declare two empty string variables, str1 and str2, to store the two original strings.

Calculate the length of the concatenatedStr.

Use a for loop to split the concatenatedStr into two original strings:

Initialize a loop variable (i) to 0.

Iterate through the characters of concatenatedStr using i.

Append each character to str1 until i reaches half the length of concatenatedStr.

Append the remaining characters to str2.

Display or use str1 and str2 as needed.

End


String Palindrome or not

Start

Declare a string variable to store the input string (inputString).

Get the input string (inputString) from the user or from any source.

Remove spaces and punctuation marks (if needed) from the input string to ensure accurate 
palindrome checking.

Declare two integer variables, left and right:

Initialize left to 0 (indicating the start of the string).

Initialize right to the length of the string minus 1 (indicating the end of the string).

Use a for loop to compare characters from the beginning and end of the string:

Initialize a loop variable (i) to 0.

Continue the loop as long as i is less than or equal to right.

In each iteration of the loop, compare inputString[left] and inputString[right]:

If they are not equal, the string is not a palindrome; break out of the loop.

If they are equal, increment left and decrement right to check the next pair of characters.

If the loop completes without breaking, the string is a palindrome.

Display a message indicating whether the string is a palindrome or not.

End


EXPECTED OUTPUT
String Display

Enter the string to display :Symbiosis

The name is :Symbiosis

String Length

Enter name: symbiosis

The inputted string is: symbiosis

The size of the string is: 9


String Concatenation and Reverse String Concatenation

SymbiosisTechnology

Length of string is :19

Given String is reversed :ygolonhceTsisoibmyS


String Palindrome or not

Enter a string: Symbiosis

sisoibmyS

Palindrome


Enter the marks of 10 subjects and display it

Marks:90 

Marks:89 

Marks:78 

Marks:87 

Marks:86 

Marks:85 

Marks:78 

Marks:98 

Marks:97 

Marks:100


Enter the marks of subjects from user and display it

Enter the marks of each subjects:
98 

Enter the marks of each subjects:
93

Enter the marks of each subjects:
92

Enter the marks of each subjects:
94

Enter the marks of each subjects:
95

Enter the marks of each subjects:
96

Enter the marks of each subjects:
91

Enter the marks of each subjects:
97

Enter the marks of each subjects:
99

Enter the marks of each subjects:
100

 Enter the marks of subjects are:

 marks:98
 
 marks:93
 
 marks:92
 
 marks:94
 
 marks:95
 
 marks:96
 
 marks:91
 
 marks:97
 
 marks:99
 
 marks:100




C++ program to find the maximum and minimum value of given array

The greatest number is: 100

The smallest number is: 45


C++ Program to find array Sum_Average

sum of the array is:1009

average of the array is:100


To Flip Element

Output:100 93 95 94 92 80 96 99 90 98

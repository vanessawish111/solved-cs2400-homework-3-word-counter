Download Link: https://assignmentchef.com/product/solved-cs2400-homework-3-word-counter
<br>
Use if statements, loops, formatting output, and strings.

Write a C++ program that counts the number of words and sentences in some text. The text will be terminated by the three symbols “@@@”.  A word is defined as a string terminated by a <em>white space</em>. A sentence will be terminated by either a period or a question mark.

Your program must output the number of words, sentences, and the average number of words per sentence rounded to one decimal place. Your program must print an error message for the average if the user enters no words or no sentences (words without a period or question mark).

<strong>Hints: </strong>

Each character in a string is stored at a certain position within the string starting with position 0. For example, consider the string “John”, the letter ‘J’ is stored at position 0, ‘o’ at position 1, etc.

We can find the length of the string by calling the function length from within the string.

string name = “John”;

int length = name.length();

This will assign 4 to the variable length.

To find the first character:

char first = name.at(0);

To find the second character:

char second = name.at(1);   //etc.

So, if you want to find the last character in the string name you would use the following:

char lastChar = name.at(length – 1);

Since we’re counting from 0, the last character will be stored at length – 1. In the example

above, the last character (‘n’) is stored at position 3;<strong>                                                </strong>

<strong>Your program must output something similar to the following: </strong>

Enter a paragraph…

@@@

Word count: 0

Sentence count: 0 You did not enter any text!

Enter a paragraph… ttt @@@

Word count: 1

Sentence count: 0

You did not enter any sentences!

Enter a paragraph…

What’s your name? My name is John. I live in Athens Ohio. I like football, how about you?

I also like to read and write computer programs. @@@

Word count: 27

Sentence count: 5

Average words per sentence: 5.4
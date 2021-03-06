# Chapter 5 Exercises

Exercises with a tick mark :ballot_box_with_check: represent exercises that must be submitted as part of your Programming Skills Portfolio as a minimum expectation. Completing more exercises provides the opportunity to attain higher marks. For each exercise you should create a _**new project**_ with the name of the exercise and save it to this exercises folder in your local repository.

Once you have completed your solution you should make sure you commit and push your solutions to your remote repository on GitHub. You can commit and push as many changes to your solutions as you wish, only those pushed before the chapter deadlines will be marked for the Programming Skills Portfolio.  

---
&nbsp;

## Exercise 1: Some counting :ballot_box_with_check:

Use your newly acquired knowledge of the for loop to complete the following tasks. Print all values to console in each case.

* Write a program that counts up from 0 to 50 in increments of 1.
* Write a program that counts down from 50 to 0 in decrements of 1.
* Write a program that counts up from 30 to 50 in increments of 1.
* Write a program that counts down from 50 to 10 in decrements of 2.
* Write a program that counts up from 100 to 200 in increments of 5.

To get you started here’s an example for loop that counts to 1000

```C++
for(int count = 0; count <= 1000; count++){
        cout << count << endl;
}
```

&nbsp;
&nbsp;

## Exercise 2: Odd or Even :ballot_box_with_check:

Using a for loop, write a programme that prints all values between 20 and 24. Then using an if-else statement and the modulus operator, modify your program to add the word “odd” or “even” to each value to show if it is odd or even.

*Expected Output:*
```
20 - even
21 - odd
22 - even
23 - odd
24 - even
```

&nbsp;
&nbsp;

## Exercise 3: Iterate through a word

The following programme uses the at() method to print each individual letter of a string (called myWord) to a new console line.
string myWord = "Joe";
cout << myWord.at(0) << endl;
cout << myWord.at(1) << endl;
cout << myWord.at(2) << endl;

```
Output:

J
o
e
```

Using the at() method in combination with a for loop, rewrite the above program to avoid duplicating cout. Note string character counts start at 0 not 1!

&nbsp;
&nbsp;

## Exercise 4: Fibonacci Sequence

This is a harder exercise. For this and the remaining exercise’s planning on paper

Watch this video for an explanation of the Fibonacci Sequence:
https://www.youtube.com/watch?v=U2L2nJl8kaw

In short, any number in the Fibonacci Sequence can be calculated by adding up the numbers both one place, and two places before it.

```
1, 1, 2, 3, 5, 8, 13….

1 + 1 = 2
1 + 2 = 3
2 + 3 = 5
3 + 5 = 8
5 + 8 = 13
```

and so on…

Using a for loop, write a programme that prints all values of the Fibonacci Sequence between 1 and 55.

Expected Result:  
```1, 1, 2, 3, 5, 8, 13, 21, 34, 55```

&nbsp;
&nbsp;

## Exercise 5: Seven Stars, Seven Lines :ballot_box_with_check:

Write a program that uses nested for loops to print the following pattern to the console

```
*******
*******
*******
*******
*******
*******
*******
```

&nbsp;
&nbsp;

## Exercise 6: Descending Stars, Seven Lines

Write a program that uses nested for loops to print the following pattern to the console

```
*******
******
*****
****
***
**
*
```

&nbsp;
&nbsp;

## Exercise 7: Rising Stars, Five Lines

Write a program that uses nested for loops to print the following pattern to the console

```
*
**
***
****
*****
```

&nbsp;
&nbsp;

## Exercise 8: Rising and Falling Stars

Write a program that uses nested for loops to print the following pattern to the console. Note you will need two sets of nested for loops, one after the other, to achieve this pattern.

```
*
**
***
****
*****
****
***
**
*
```

&nbsp;
&nbsp;

## Exercise 9: Cubes			
Write a program using a for loop to display the cube of the numbers upto an integer entered by the user. Only a single for loop is required for this exercise.

The cube of a number can be calculated by multiplying a number by itself twice (e.g. the cube of 2 is 8 → 2 x 2 x 2).

*Expected output if user enters 5:*

```
Number is : 1 and the cube of 1 is: 1                                  
Number is : 2 and the cube of 2 is: 8                                  
Number is : 3 and the cube of 3 is: 27                                 
Number is : 4 and the cube of 4 is: 64                                 
Number is : 5 and the cube of 5 is: 125
```

&nbsp;
&nbsp;

## Exercise 10: Find the 9s

Write a program to find the number and sum of all integers between 100 and 200 which are divisible by 9. Only a single for loop is required for this exercise.

&nbsp;
&nbsp;

## Exercise 11: Multiplication :ballot_box_with_check:
Using a nested for loop write a program that outputs the 1 - 12 times table.

*Sample output:*

```
1 times table:
---------------

1 x 1 = 1
1 x 2 = 2
1 x 3 = 3
1 x 4 = 4
1 x 5 = 5
1 x 6 = 6
1 x 7 = 7
1 x 8 = 8
1 x 9 = 9
1 x 10 = 10
1 x 11 = 11
1 x 12 = 12


2 times table:
---------------

2 x 1 = 2
2 x 2 = 4
2 x 3 = 6
2 x 4 = 8
2 x 5 = 10
2 x 6 = 12
2 x 7 = 14
2 x 8 = 16
2 x 9 = 18
2 x 10 = 20
2 x 11 = 22
2 x 12 = 24
```

&nbsp;
&nbsp;

## Exercise 12: Reverse it

Write a program that finds the reverse of a number. For example:

```
Input: 12345
Output: 54321
```

&nbsp;
&nbsp;

## Exercise 13: For Loop Fixer

```C++
int n = 3;
for(int i = 0; i<n ; i--){
    cout << "*";
}
```

Stop this infinite looping by removing or changing just one character so that it prints the asterix.

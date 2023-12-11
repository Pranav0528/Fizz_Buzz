# Fizz_Buzz
Fizz Buzz Challenge

The provided code is a Python program that implements the classic FizzBuzz problem. The FizzBuzz problem is a common coding exercise where you iterate through a range of numbers and perform certain actions based on the conditions given. Here's a summary of the code:

number = 100: Initializes a variable number with the value 100.

for i in range(1, number+1):: Iterates through the numbers from 1 to 100 (inclusive).

Inside the loop, the code checks three conditions for each number:

If the number is divisible by both 3 and 5 ((i % 3 == 0) and (i % 5 == 0)), it prints "FizzBuzz."
If the number is only divisible by 3 (elif i % 3 == 0), it prints "Fizz."
If the number is only divisible by 5 (elif i % 5 == 0), it prints "Buzz."
If none of the above conditions are met, it prints the current number (else: print(i)).
The output of the program is a sequence of numbers from 1 to 100, with "Fizz" for numbers divisible by 3, "Buzz" for numbers divisible by 5, and "FizzBuzz" for numbers divisible by both 3 and 5.

👩‍🏫 HackerRank Day 4: Class vs. Instance - Python

This repository includes the Python solution to the HackerRank 30 Days of Code - Day 4: Class vs. Instance challenge.

It demonstrates object-oriented programming using classes, constructors, and methods.


🧠 Problem Statement

Create a Person class with:

An integer attribute age.

A constructor that initializes age:

If the given age is negative, print "Age is not valid, setting age to 0." and set age to 0.

A method amIOld() that prints:

"You are young." if age < 13

"You are a teenager." if 13 ≤ age < 18

"You are old." otherwise

A method yearPasses() that increments the person's age by 1.


📥 Input Format

The first line contains an integer, t, the number of test cases.

The following t lines each contain an integer indicating the age.


🧾 Sample Input

4

-1

10

16

18


📤 Output Format

Print appropriate messages based on the person's age before and after 3 years pass.


🧾 Sample Output

Age is not valid, setting age to 0.

You are young.

You are young.


You are young.

You are a teenager.


You are a teenager.

You are old.


You are old.

You are old.


📚 Topics Covered

Object-Oriented Programming (OOP)

Python Classes and Constructors

Conditional Statements

Input/Output Handling


How to Run: 

Option 1: With input file Create a file named input.txt with the required input and run: python3 class_vs_instance.py < input.txt

Option 2: Manual input Just run: python3 class_vs_instance.py


🏅 HackerRank Score

✅ Challenge Completed

🏆 Points Earned: 30


🔗 HackerRank Challenge Link: HackerRank - Day 4: Class vs. Instance 

✍ Author: Harshaharika7


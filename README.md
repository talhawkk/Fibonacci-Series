# Fibonacci-Series
<b><h1>Fibonacci Series using Recursion in Python</h1></b>
This repository contains a Python implementation of the Fibonacci series using recursion.<br> The program takes an input from the user, specifying the number of terms, and outputs the Fibonacci sequence up to that number.<br>

<h2>Program Overview</h2>
The program defines a recursive function fs(n) that calculates the Fibonacci number for a given n based on the following logic:<br>

<b>Base Case</b>: If n is 0 or 1, return n.
Recursive Case: For any other value of n, return the sum of the two previous Fibonacci numbers: fs(n-1) + fs(n-2).<br>
<b>How it works:</b><br>
The user inputs the number of terms they want to see in the Fibonacci sequence.
If the input is less than 1, the program prompts the user to enter a valid number.
The Fibonacci sequence is printed using the recursive function.
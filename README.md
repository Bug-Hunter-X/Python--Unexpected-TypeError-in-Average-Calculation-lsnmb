# Python: Unexpected TypeError in Average Calculation

This repository demonstrates a common error in Python code:  a `TypeError` that occurs when attempting to calculate the average of a list containing non-numeric values.

The `bug.py` file shows the code with the error. The `bugSolution.py` file provides a corrected version.

## Problem

The original code calculates the average of numbers in a list. However, it lacks input validation, failing if the input list contains non-numeric data types. 

## Solution

The improved code includes a check to ensure all items in the list are numbers before performing the calculation, thus preventing the `TypeError`.
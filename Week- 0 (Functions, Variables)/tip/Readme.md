Problem: Tip Calculator

Write a Python program that calculates a tip for a meal based on the cost and desired percentage.

Details:

Implement a function dollars_to_float that:

Accepts a string formatted as $##.##

Removes the $ and returns the amount as a float

Example: $50.00 → 50.0

Implement a function percent_to_float that:

Accepts a string formatted as ##%

Removes the % and returns the percentage as a float

Example: 15% → 0.15

The program should prompt the user for the meal cost and tip percentage, then print the tip amount as a float with two decimal places.

Assume inputs are always in the correct format.

Examples:
Input: $50.00, 15%
Output: Leave $7.50

Input: $100.00, 18%
Output: Leave $18.00

Input: $15.00, 25%
Output: Leave $3.75

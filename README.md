# VIP-7

# Leap Year- Functions
A common year in the modern Gregorian Calendar consists of 365 days. In reality, Earth takes longer to rotate around the sun. To account for the difference in time, every 4 years, a leap year takes place. A leap year is when a year has 366 days: An extra day, February 29th. The requirements for a given year to be a leap year are:

1) The year must be divisible by 4

2) If the year is a century year (1700, 1800, etc.), the year must be evenly divisible by 400; therefore, both 1700 and 1800 are not leap years

Some example leap years are 1600, 1712, and 2016.

Write a program that takes in a year and determines the number of days in February for that year.

Ex: If the input is:

1712
the output is:

1712 has 29 days in February. 
Ex: If the input is:

1913
the output is:

1913 has 28 days in February.
Your program must define and call the following function. The function should return the number of days in February for the input year.
def days_in_feb(user_year)

# Max Magnitude
Write a function max_magnitude() with three integer parameters that returns the largest magnitude value. Use the function in the main program that takes three integer inputs and outputs the largest magnitude value.

Ex: If the inputs are:

5
7
9
function max_magnitude() returns and the main program outputs:

9
Ex: If the inputs are:

-17
-8
-2
function max_magnitude() returns and the main program outputs:

-17
Note: The function does not just return the largest value, which for -17 -8 -2 would be -2. Though not necessary, you may use the built-in absolute value function to determine the max magnitude, but you must still output the input number (Ex: Output -17, not 17).

Your program must define and call the following function:
def max_magnitude(user_val1, user_val2, user_val3)

# Multiples of Ten in a List
Write a program that reads a list of integers, and outputs whether the list contains all multiples of 10, no multiples of 10, or mixed values. Define a function named is_list_mult10 that takes a list as a parameter, and returns a boolean that represents whether the list contains all multiples of ten. Define a function named is_list_no_mult10 that takes a list as a parameter and returns a boolean that represents whether the list contains no multiples of ten.

Then, write a main program that takes an integer, representing the size of the list, followed by the list values. The first integer is not in the list.

Ex: If the input is:

5
20
40
60
80
100
the output is:

all multiples of 10
Ex: If the input is:

5
11
-32
53
-74
95
the output is:

no multiples of 10
Ex: If the input is:

5
10
25
30
40
55
the output is:

mixed values
The program must define and call the following two functions. is_list_mult10() returns true if all integers in the list are multiples of 10 and false otherwise. is_list_no_mult10() returns true if no integers in the list are multiples of 10 and false otherwise.
def is_list_mult10(my_list)
def is_list_no_mult10(my_list)

# Step Counter
A pedometer treats walking 1 step as walking 2.5 feet. Define a function named feet_to_steps that takes a float as a parameter, representing the number of feet walked, and returns an integer that represents the number of steps walked. Then, write a main program that reads the number of feet walked as an input, calls function feet_to_steps() with the input as an argument, and outputs the number of steps as an integer.

Use floating-point arithmetic to perform the conversion.

Ex: If the input is:

150.5
the output is:

60
The program must define and call the following function:
def feet_to_steps(user_feet)

# Aggie Group Problem
Maintaining physical health during your time at TAMU is important. TAMU offers multiple facilities for group classes and individual workouts. The facilities are open at a wide range of convenient times.

Your task today is to research exercise options for TAMU students and create a Python program that creates a rough exercise plan. Write the program using functions. Follow the guidelines below.

Function 1

Create a function that uses input() to ask the user for the number of minutes they plan to exercise each day of the week. The function should return a list containing the number of minutes the user will exercise each day.

Function 2

Create a function that takes as an argument the list returned by Function 1. Function 2 should print the total hours exercised in the week.

Function 3

Research: For each day of the week, choose a recreation facility. Record that facility’s hours and a few exercise activities that you would like to do at that location. You may repeat facilities and activities for multiple days of the week. Hours on the websites below  might be listed for Summer currently, do your best to find Fall/Spring hours.

TAMU CS Fitness Resources: https://recsports.tamu.edu/
TAMUG Fitness Resources: https://www.tamug.edu/campusrec/index.html
Coding: Create a function that takes as an argument the list output by Function 1. For each day that you will exercise, print the minutes you will exercise as well as your researched location, hours, and activities. Only print for days that you will actually exercise based on list from Function 1.



Example Output

How many minutes will you exercise on Monday?: 0
How many minutes will you exercise on Tuesday?: 45
How many minutes will you exercise on Wednesday?: 0
How many minutes will you exercise on Thursday?: 0
How many minutes will you exercise on Friday?: 100
How many minutes will you exercise on Saturday?: 0
How many minutes will you exercise on Sunday?: 0
You will exercise for 2.42 hours this week.

Tuesday: 45 minutes
Main Student Rec Center
   Activities: weightlifting, treadmill cardio, basketball
   Hours: 6 AM - 12AM


Friday: 100 minutes
Penberthy Field
   Activities: soccer, intramural flag football
   Hours: 9 AM - 12AM

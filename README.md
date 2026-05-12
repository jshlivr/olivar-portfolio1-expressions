Program: Study Reward System Calculator
Created by : Jashlia Martha D. Olivar BSChE-1B
Introduction : The objective of this portfolio is to apply the fundamental programming building blocks
discussed in Chapter 2: Variables, Expressions, and Statements. This application is a Study Reward
Calculator designed to incentivize academic consistency. The program utilizes the input() function to
interact with the user, pausing to read the number of hours they have studied per day. Because the
input() function natively returns data as a string, I utilized type conversion, specifically the float() to
transform that input into a numeric type that Python can process mathematically so I can add all input
per day collectively as a total of hours studied per week. The core of the program relies on numeric
expressions, where classic math operations such as multiplication (*) and addition (+) are used to evaluate
a student's total study hours and calculate their corresponding monetary allowance in Pesos. Through this
project, I demonstrate how assignment statements can take an expression on the right-hand side and
store the resulting value in a variable for final output.
Concepts Used:
Constants: I set fixed numeric values like 50 for my reward rate because these values do not change
while the program is running.
Mnemonic Variables: I picked descriptive names like study_hours and total_allowance to help me
remember exactly what data I was storing in the computer's memory.
User Input: I used the input() function to make my program pause and wait for me to type in my
study hours.
Type Conversion: Since input() always gives me text (a string), I used the float() or int() functions to
convert that text into a number so I could perform math.
Assignment Statements: I used the = sign to take the result of my calculations and store it into my
variables.
Numeric Expressions: I used the asterisk * for multiplication and the plus sign + for addition to
calculate my total rewards.
Comments: I used the # symbol to write notes in my code, documenting what each part of my
program was doing for anyone reading it.
# Input of number of hours for each day of the week
# Instead of int I used float so it can have decimal places instead of rounding it off
print('Enter the number of hours you studied')
hours1_input = float(input('Monday : '))
hours2_input = float(input('Tuesday : '))
hours3_input = float(input('Wednesday : '))
hours4_input = float(input('Thursday : '))
hours5_input = float(input('Friday : '))
hours6_input = float(input('Saturday : '))
hours7_input = float(input('Sunday : '))
Enter the number of hours you studied
# Totals the hr studied for the whole week
hrs = hours1_input + hours2_input + hours3_input + hours4_input + hours5_input + hours6_input
print('Total hours:', hrs)
Total hours: 15.8
In [2]: In [3]:
# Setting a new name for the variable
study_hours = float(hrs)
# Defining the constant allowance rate per hour studied
pesos_per_hour = 25
# Calculate the total allowance
# Multiplication expression 
total_allowance = study_hours * pesos_per_hour
# Output the results to the user
print('--- Study Reward Summary ---')
print('Hours Studied :', study_hours, 'hours')
print('Total Reward : Php', total_allowance)
--- Study Reward Summary ---
Hours Studied : 15.8 hours
Total Reward : Php 395.0

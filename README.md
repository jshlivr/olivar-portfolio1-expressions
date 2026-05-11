Program: Study Reward System Calculator
Purpose : Calculates maximum amount of reward (in pesos) based on study hours in a week.
Rule : 1 hour studied = 50 pesos allowance.

#Input of number of hours for each day of the week
#Instead of int I used float so it can have decimal places instead of rounding it off
print('Enter the number of hours you studied')
hours1_input = float(input('Monday : '))
hours2_input = float(input('Tuesday : '))
hours3_input = float(input('Wednesday : '))
hours4_input = float(input('Thursday : '))
hours5_input = float(input('Friday : '))
hours6_input = float(input('Saturday : '))
hours7_input = float(input('Sunday : '))


#Totals the hr studied for the whole week
hrs = hours1_input + hours2_input + hours3_input + hours4_input + hours5_input + hours6_input + hours7_input
print('Total hours:', hrs)
Total hours: (insert number of hrs)

Setting a new name for the variable
study_hours = float(hrs)

#Defining the constant allowance rate per hour studied
pesos_per_hour = (insert rate)

#Calculate the total allowance
#Multiplication expression 
total_allowance = study_hours * pesos_per_hour

#Output the results to the user
print('--- Study Reward Summary ---')
print('Hours Studied :', study_hours, 'hours')
print('Total Reward : Php', total_allowance)
--- Study Reward Summary ---
Hours Studied : (insert) hours
Total Reward : Php (insert)

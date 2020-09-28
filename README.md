#INST126-Fall-2020

#Calculator

#Here you ask the user to input their numbers

operation = input('''
Please type the math operation you would like to complete:
+ for addition you use a plus sign 
- for subtraction a subtraction sign 
* for multiplication a star sign 
/ for division a slash sign
 

#this is where variables are defined

number_1 = int(input('Enter your first number: '))

number_2 = int(input('Enter your second number: '))

#You use conditional statements to perform the operations  

#the variables are substituting the user input and are used in functions to perform the operation 

if operation == '+':
    print('{} + {} = '.format(number_1, number_2))
    print(number_1 + number_2)

elif operation == '-':
    print('{} - {} = '.format(number_1, number_2))
    print(number_1 - number_2)

elif operation == '*':
    print('{} * {} = '.format(number_1, number_2))
    print(number_1 * number_2)

elif operation == '/':
    print('{} / {} = '.format(number_1, number_2))
    print(number_1 / number_2)
    
#if none of the above work we use else 

else:
    print('You have not typed a valid operator,.')

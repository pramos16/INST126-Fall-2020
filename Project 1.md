```python
#asks user for input
operation = input('''
Please type the math operation you would like to complete:
+ for addition
- for subtraction
* for multiplication
/ for division
''')
#this is where variables are defined
number_1 = int(input('Enter your first number: '))
number_2 = int(input('Enter your second number: '))
#these are the conditional statements 
#variables being used in functions to perform the calculation
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

else:
    print('You have not typed a valid operator,.')
```

    
    Please type the math operation you would like to complete:
    + for addition
    - for subtraction
    * for multiplication
    / for division
    /
    Enter your first number: 5
    Enter your second number: 5
    5 / 5 = 
    1.0



```python

```


```python

```

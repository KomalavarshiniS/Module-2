# EX-06-Built-in Functions -Binary Conversion Using Built-in Functions in Python

## Aim
To write a Python program to return  the Boolean value of an object using inbuilt function.

## Algorithm
1.Take input from the user and store it in a variable.
2.Use the built-in bool() function to get the Boolean value of the input.
3. Print the result.

## Program
```
Developed by: KOMALAVARSHINI.S
Register Number: 212224230133
value=input()
try:
    value=int(value)
except ValueError:
    pass
print("Boolean value is:",(bool(value)))
```

## Output
![image](https://github.com/user-attachments/assets/cae8743c-670c-43ef-8dd7-6f6ecb86b978)

## Result
Thus the program to return  the Boolean value of an object using inbuilt function has been executed successfully.
# Ex-07-Functions in Python: Modulo Calculator

## Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## Program
```
Developed by: KOMALAVARSHINI.S
Register Number:212224230133
a=int(input())
b=int(input())
def result(a,b):
    modulo=a%b
    return int(modulo)
print("modulo is",result(a,b))
```


## Output
![image](https://github.com/user-attachments/assets/3cc497ae-a4ae-4271-92d4-c3de90d589ca)

## Result
Thus the program that defines a function which accepts two values and returns their **modulo** using the `%` operator has been executed successfully.
# EX-08-Lambda Function in Python: Addition of Two Numbers

## Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their mul.

## Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a * b`.
3. Call the function with the user inputs and print the result.

## Program
```
Developed by: KOMALAVARSHINI.S
Register Number: 212224230133
def mul(a,b):
    m=a*b
    return m
a=int(input ())
b=int(input ())

print(mul(a,b))
```

## Output
![image](https://github.com/user-attachments/assets/468db9a8-c9d3-4b90-bc9c-6b4d7cf6efee)

## Result
 Thus the program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their mul has been executed successfully.
# EX-09-Looping(Patterns)-Pascal's Triangle Generator in Python
This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.
## Aim
To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.
## Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
    num = num * (i - j) // (j + 1) 
5. Print all rows of Pascal’s Triangle.
6. End the program.

## Program
```
Developed by: KOMALAVARSHINI.S
Register Number: 212224230133
def pascal_triangle(n):
    for i in range(n):
        num = 1
        for j in range(i + 1):
            print(num, end=' ')
            num = num * (i - j) // (j + 1)
        print()  # Move to the next row

# Get input from the user
rows = int(input())
pascal_triangle(rows)
```

## Sample Output
![image](https://github.com/user-attachments/assets/c57d0370-a159-4a83-976b-c81dec67b6c4)

## Result 
Thus the program to generate **Pascal’s Triangle**, where the number of rows is provided by the user has been executed successfully.
# EX-10-Loops in Python: Palindrome Number Checker

## Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## Program
```
Developed by:KOMALAVARSHINI.S
Register Number:212224230133
n=int(input())
temp=n
rev=0
while n>0:
    digit=n%10
    rev=rev*10+digit
    n=n//10
if temp==rev:
    print(f"The given number {temp} is a Palindrome")
else:
    print(f"The given number {temp} is not a palindrome")
```
## Output
![image](https://github.com/user-attachments/assets/ec8ae68a-1487-44d2-84f6-b4fad4235c4d)

## Result
Thus the program that checks whether a given number is a **palindrome** using loops has been executed successfully.

# Conditional Statements in Python: Even or Odd Checker

## 🎯 Aim
To write a Python program to check whether the given number is **even** or **odd** using `if...else` statements.

## 🧠 Algorithm
1. Get an input from the user.
2. Convert the input to an integer and store it in a variable `a`.
3. Use the modulo operator `%` to check if `a % 2 == 0`.
   - If true, print `"EVEN"`.
   - Else, print `"ODD"`.
4. End the program.

## 🧾 Program
```

num = int(input("Enter a number: "))

if num % 2 == 0:
    print("Even")
else:
    print("Odd")
```

## Output
<img width="686" height="764" alt="image" src="https://github.com/user-attachments/assets/d6262651-35c1-423e-8687-9fdb3e4d8ff2" />

## Result
The program successfully checks whether the given number is Even or Odd using the if...else statement.


# Ex 1:Datatypes-Boolean Expression Evaluation in Python

## 🎯 Aim
To write a Python program that evaluates and prints the results of boolean and arithmetic expressions involving `True` and `False`.

## 🧠 Algorithm
1. Set variable `a` to the result of the expression `0 == True`.
2. Set variable `b` to the result of the expression `False == False`.
3. Set variable `c` to the result of the expression `True + True`.
4. Set variable `d` to the result of the expression `False + 9`.
5. Print the value of `a` with the label "a is".
6. Print the value of `b` with the label "b is".
7. Print the value of `c` with the label "c:".
8. Print the value of `d` with the label "d:".

## 💻 Program
```
a = (0 == True)
b = (False == False)
c = (True + True)
d = (False + 9)

print("a is", a)
print("b is", b)
print("c:", c)
print("d:", d)
```
## Output
<img width="400" height="800" alt="image" src="https://github.com/user-attachments/assets/4bdc8938-35cb-4f02-9165-199ba2eef9f1" />

## Result
The program successfully evaluates and prints the results of the given boolean and arithmetic expressions involving True and False.


# Ex 1:Datatypes-Boolean Expression Evaluation in Python

## 🎯 Aim
To write a Python program that evaluates and prints the results of boolean and arithmetic expressions involving `True` and `False`.

## 🧠 Algorithm
1. Set variable `a` to the result of the expression `0 == True`.
2. Set variable `b` to the result of the expression `False == False`.
3. Set variable `c` to the result of the expression `True + True`.
4. Set variable `d` to the result of the expression `False + 9`.
5. Print the value of `a` with the label "a is".
6. Print the value of `b` with the label "b is".
7. Print the value of `c` with the label "c:".
8. Print the value of `d` with the label "d:".

## 💻 Program
```
a = (0 == True)
b = (False == False)
c = (True + True)
d = (False + 9)

print("a is", a)
print("b is", b)
print("c:", c)
print("d:", d)
```
## Output
<img width="400" height="800" alt="image" src="https://github.com/user-attachments/assets/4bdc8938-35cb-4f02-9165-199ba2eef9f1" />

## Result
The program successfully evaluates and prints the results of the given boolean and arithmetic expressions involving True and False.

# 🧮 Datatypes-Complex Number Creation in Python

## 🎯 Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

## 🧠 Algorithm
1. Read an integer input from the user and assign it to the variable `a` (real part).
2. Read another integer input from the user and assign it to the variable `b` (imaginary part).
3. Create a complex number `x` using the `complex(a, b)` function.
4. Print the complex number `x`.
5. Print the real part of `x` using `x.real`.
6. Print the imaginary part of `x` using `x.imag`.

## 💻 Program
```
a = int(input("Enter real part: "))
b = int(input("Enter imaginary part: "))

x = complex(a, b)

print("Complex Number =", x)
print("Real Part =", x.real)
print("Imaginary Part =", x.imag)
```

## Output
<img width="1471" height="380" alt="image" src="https://github.com/user-attachments/assets/e37ad8df-b366-42e5-bc72-6b3189d4f131" />

## Result
The program was executed successfully and printed the complex number along with its real and imaginary parts.



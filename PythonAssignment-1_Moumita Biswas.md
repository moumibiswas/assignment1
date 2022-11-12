## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?
A1. Python is called a general purpose language because it has application in varied domains. Unlike a domain-specific language (DSL), it is not specified for a particular domain and is a beginner-friendly language as well. It is considered high -level programming language as it has been developed for easy understanding of humans and not written in machine-readable format, that is, low-level language. 

Q2. Why is Python called a dynamically typed language?
A2. Python is called a dynamically type language because the type of the variable is assigned only during the runtime. There is no nessecity to declare the type of the variable in the written code.

Q3. List some pros and cons of Python programming language?
A3. Some pros of Python programming language are:
a. It is a beginner-friendly language as it is easy to read and use by humans
b. Python developers have made it open-source for everyone to use it for free
c. A large community to support anyone who needs insights
d. It has a huge collection of libraries for different application
e. It is portable and scalable programming language
Some cons of Python programming language are:
a. It is slower than compiled languages and thus, one major drawback is the speed limitation
b. It does not support much of mobile environment
c. It has a huge memory consumption
d. It shows runtime error for its dynamically typed feature

Q4. In what all domains can we use Python?
A4. Python has a wide variety of domains applicability, such as, data engineering, data science, web development, machine learning/artificial intelligence, mobile app development, etc.

Q5. What are variable and how can we declare them?
A5. A variable is used to store values or information in the memory. It is a reference that can retrieve stored values from the memory location as and when required. It can be declared by writing the type before the name of the variable and assigning it a value. In Python, mentioning a type is not needed, it gets declare just through assignment of the value.

Q6. How can we take an input from the user in Python?
A6. Input can be taken by using the function 'input()' and putting a string into the prompt of the function. For example: x = input("Enter the value of x:").

Q7. What is the default datatype of the value that has been taken as an input using input() function?
A7. The input() function as string as its default datatype of the value.

Q8. What is type casting?
A8. Type casting is the method of converting one data type to another datatype. For example, x = 2 is int type and then changing it to y = float(x) with y as float.

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
A9. No, we can take only one input from the user using single input() function as only one value can be assigned to the variable for which the input is being taken. To take more than one value, another function split() needs to be used along with the input() function.

Q10. What are keywords?
A10. Python keywords are reserved words that have specific purposes to define the syntax of the language and cannot be used for any other purpose.

Q11. Can we use keywords as a variable? Support your answer with reason.
A11. No, keywords cannot be used as a variable because they have special meanings. The keywords, such as 'and', 'or', 'if', etc. are logical operators that consturct the structure needed to implement the python language.

Q12. What is indentation? What's the use of indentaion in Python?
A12. Indentation is the spaces put at the begining of a codee line. It is very important in Python as it defines a block of code, that is, a group of statements that performs a particular task together.

Q13. How can we throw some output in Python?
A13. To get output in Python, the most commonly used function is print().

Q14. What are operators in Python?
A14. Operators in Python are used to perform mathematical operations (+, -, *, etc.), assign values to variable (=, +=, /=, etc.), compare variables and return a boolean result (True, False).

Q15. What is difference between / and // operators?
A15. Operator / is used for float division whereas // is used for interger divsion.

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
A16. 
str_data = 'iNeuron'
str_result = str_data * 4
print("'''\n", str_result, "\n'''")

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
A17. 
num = int(input("Enter a number: "))
if num % 2 == 0:
    print("The number", num, "is even.")
else:
    print("The number", num, "is odd.")

Q18. What are boolean operator?
A18. Boolean operators are the keywords 'and', 'or', 'not' that are used in various combination to perform some logical operations. True and False are also considered boolean operators.

Q19. What will the output of the following?
```
1 or 0

0 and 0

True and False and True

1 or 0 or 0
```
A19: Output:
1
0
False
1

Q20. What are conditional statements in Python?
A20. Conditional statements in Python are used for decision-making operations. The conditional operators run a particular block of code only when a certain condition is satisfied.

Q21. What is use of 'if', 'elif' and 'else' keywords?
A21. 'if', 'elif' and 'else' keywords are used to check multiple expressions. The first condition begins with 'if', the next set of conditions begin with 'elif' and the last condition or whatever is left is put to 'else' keyword.

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
A22.
age = int(input("Enter the age of a person: "))
if age >= 18:
    print("I can vote")
else:
    print("I can't vote")

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
A23:
numbers = [12, 75, 150, 180, 145, 525, 50]
sum = 0
for num in numbers:
    if num % 2 == 0:
        sum += num
print("The sum of all the even numbers from the given list is", sum)

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
A24:
numbers = input("Enter three numbers: ")
num = [int(n) for n in numbers.split()]
m = max(num)
print("The greatest number is:", m)

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
A25. 
numbers = [12, 75, 150, 180, 145, 525, 50]
num = []
for n in numbers:
    if n > 150:
        if n > 500:
            break
        continue
    if n % 5 == 0:
        num.append(n)
print("The list of numbers that satisfy the conditions:", num)

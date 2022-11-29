# Ineuron-Assignment Part-1
## Big Data Course

Q1. Why do we call Python as a general purpose and high-level programming language?

``
In Python basically the code written human language and then it is converted into the machine language by using interpretor, as the process is being easy for us to understand that how python is a general purpose and high level language ``

Q2. Why is Python called a dynamically typed language?

``In python there no need to enter the data variable typr i.e; int x=2; rather we can use x=2 in dynamically typed language rather statically typed language and aslo Dynamically typed language is Run Time process and Statically typed Language is Compile Time``

Q3. List some pros and cons of Python programming language?

`Python is a high level, Interpreted, and Dynamically Typed Language which it has pros and cons like firstly Pros are compilation speed is faster, Portability is Good, but cons are the Execution Time taken by Python is slower then the other Complier language like java`

Q4. In what all domains can we use Python?

`Python programming language is used for domains such as artificial intelligence, machine learning and deep learning, it's also a fundamental tool for any data Analysis and Visulation`

Q5. What are variable and how can we declare them?

`Variables are like naming the object that can be stored in anywere in the memory location when there is a need we can use te name to call the object`
i.e; 
```python
X=2 
print(X)
print(type(X))
```

Q6. How can we take an input from the user in Python?

```python
string = "Big Data iNeuron"
#desired_output = "norueNi"
print("\nThe Default Input -",string)
print("\nThe Length Of The  Input -",len(string))
print("\nAs The Desired Output -",string[-1::-1])#By simply adding the numerial calc in the reverse manner
```

`we can the user input as declaring common human language `
i.e; 
```python
M=int(input("Random value"))
print("the value of M is",M)
print("data type of M is ",type(M))
```

Q7. What is the default datatype of the value that has been taken as an input using input() function?

`the default datatype of the value that has been taken as an input using input() function is str() - String data type in python `


Q8. What is type casting?

`Type casting is a process that change the nature of Intiger to Float and Float to Intiger `i.e; 
```python
M=float(input("Random no. decimal value ",)), 
print("the value of M is",M), 
print("data type of M is ",type(M)), 
print("data type of M had changed to Intiger is ",int(M))
```
Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?

`yes we can use one input function or more than one input from users,`
i.e;
```python
A,B,C,D,E,F,G=input("Enter the Seven Value ",).split()
print("First number is {}, second number is {}, third number is {}, fourth is {}, Five number is {}, Six number is {}, Seven number is {}".format(A, B, C, D, E, F, G)) 
```
Q10. What are keywords?

`Python has a set of keywords that are reserved words that cannot be used as variable names, function names, or any other identifiers ,i.e; Append,and,not,or,str,class ,type.`

Q11. Can we use keywords as a variable? Support your answer with reason.

`We cannot use a keyword as a variable name, function name, or any other identifier. They are used to define the syntax and structure of the Python language.
All the keywords except True, False and None are in lowercase i.e; true,false,none and they must be written as they are. The list of all the keywords is given below.`

Q12. What is indentation? What's the use of indentaion in Python?

`The identification of a block of code in Python is done using Indentation. In many different programming languages like C, C++, Java, etc. use flower brackets or braces {} to define or to identify a block of code in the program, whereas in Python, it is done using the spaces or tabs, which is known as indentation.`
i.e;
```python
n = 10
if n>5:
print ("n is greater than 5")
else:
print ("n is not greater than 5")
```
Q13. How can we throw some output in Python?

`We can throw an Exeption Output by using raise() Function` - i.e; 
```python
raise NameError("Hello") 
```

Q14. What are operators in Python?

`Operators re the main features in python Assign, Declare, etc,.. There are three # Arithmatic # Logical # Assignment - i.e; + - * /, += -= /=, > < != ==. `


Q15. What is difference between / and // operators? 

`the difference between / and // in Arithimatic operators are ( / ) this operator is used for Float Division and ( // ) this operator used for intiger Division.`

Q16. Write a code that gives following as an output.

iNeuroniNeuroniNeuroniNeuron

Ans;
```python
A="iNeuron"
A*=4
print("The Desired Output is",A)
```

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
```python
Number=int(input("enter a value to find if the number is odd or even ",))
Boomer=Number%2
if Boomer==0:
    print("Yes, The {0} Is Even !!".format(Number))
else:
    print("No, The {0} Is Odd !!".format(Number))
 ```
Q18. What are boolean operator?

`Boolean Operator is a decision making Operator which compare the two operant value and give the output `
- i.e; 
```python
A=10
B=5
print("Result of a == b , ", A == B)
```

Q19. What will the output of the following?

1 or 0

0 and 0

True and False and True

1 or 0 or 0

`Output is empty because we did't declare the print() function for output`

Q20. What are conditional statements in Python?

`In python we have some looping function that are need to ended or it will keep on looping , Because of that we have some condition that loop will get stop and they three given below *if-else, *if elif else, *Nested if.`

Q21. What is use of 'if', 'elif' and 'else' keywords?

`*if keyword is a control flow statement which enables us to execute a part of the software script only when a certain condition is satisfied. *elif keyword is shorthand for else if. This keyword is used in conjunction with if statements. *The else keyword catches anything which is not caught by the preceding conditions. This keyword is used in conjunction with if statements`

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

```python
age = int(input("Enter your age: "))
if age >= 18:
    print("I can vote")
else:
    print("I can't vote")
```

Q23. Write a code that displays the sum of all the even numbers from the given list.

numbers = [12, 75, 150, 180, 145, 525, 50]

```python
a=[12, 75, 150, 180, 145, 525, 50] # only even no, contion needed 
b=0
for c in a : # changing,the variable address to make list multily by int
    if (not(c%2 and c//2)):
        b+=c # only even no.satisfy the above contidion 
        print("The Addition Of Even No. In the List ",b)
```

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

```python
Numbers1,Numbers2,Numbers3=input("Enter The First Random No. "),input("Enter The Second Random No. "),input("Enter The Third Random No. ")
if(Numbers1>Numbers2):
    if(Numbers1>Numbers3):
        print("First no.{} is the Greatest Of all three number which you entered.".format(Numbers1))
elif(Numbers2>Numbers3):
    print("Second no.{} is the Greatest Of all three number which you entered.".format(Numbers2))
else:
    print("Third no.{} is the Greatest Of all three number which you entered.".format(Numbers3))
```

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

The number must be divisible by five

If the number is greater than 150, then skip it and move to the next number

If the number is greater than 500, then stop the loop

numbers = [12, 75, 150, 180, 145, 525, 50]

```python
numbers = [12, 75, 150, 180, 145, 525, 50]
swap = 0
for spare_key in numbers:
    if (not(spare_key%5)):
        if (spare_key>500 ):
            break #where the no. after 500 get omitted
        elif(spare_key<=150 ):
            print("Numbers that satisfied by following conditions",spare_key)
```

Q26. What is a string? How can we declare string in Python?

`String is sequence of letter that are pre defined by the function in python and we can declare strings by using " " or' ' these two symboles are used to declare`
```python
x='Bumbblebeee'
print("",x)
print("",type(x))
```

Q27. How can we access the string using its index?

`You can access the characters in a string by referring to its index number inside square brackets []`

Q28. Write a code to get the desired output of the following

string = "Big Data iNeuron"
desired_output = "iNeuron"

```python
string = "Big Data iNeuron"
#desired_output = "iNeuron"
print("\nThe Default Input -",string)
print("\nThe Length Of The  Input -",len(string))
print("\nAs The Desired Output -",string[9:16])
```

Q29. Write a code to get the desired output of the following

string = "Big Data iNeuron"
desired_output = "norueNi"

```python
string = "Big Data iNeuron"
#desired_output = "norueNi"
print("\nThe Default Input -",string)
print("\nThe Length Of The  Input -",len(string))
print("\nAs The Desired Output -",string[-1:-8:-1])#we need count the from reverse to print the value or string in the reverse - i.e;(-1=the last index, -2=the Second last index)
```

Q30. Resverse the string given in the above question.

```python
string = "Big Data iNeuron"
#desired_output = "norueNi"
print("\nThe Default Input -",string)
print("\nThe Length Of The  Input -",len(string))
print("\nAs The Desired Output -",string[-1::-1])#just by adding the numerical reverse manner 
```

Q31. How can you delete entire string at once?

`By Simply Using The Del Variable Name` - i.e;
```python
A="That Girl Has A Beautiful Nepals "
del A
print("",A)
```

Q32. What is escape sequence?

`Escape sequences allow you to include special characters in strings` - i.e;
```python
\	Backslash (\)
'	Single quote (')
"	Double quote (")
```

Q33. How can you print the below string?

'iNeuron's Big Data Course'
```python
#A = 'iNeuron's Big Data Course'#In this we can't declare a string like thing because '' once closed and ' another function is called but un functioned by not completing it
A = "iNeuron's Big Data Course"#By doing these we can achive the printing method
print("",A)
```

Q34. What is a list in Python?

`A List in A python is known as sequence data type which is that we can include in the element list as String, Int, Float where as in array we can't enter an hetrogenous data type because array is a homogenous data type`

Q35. How can you create a list in Python?

`We a create a List in python by using square bracket Variable_name [] ` - i.e;
```python
Apple = []
Apple.append(50)
Apple.append(60)
print("",Apple)
```

Q36. How can we access the elements in a list?

```python
Box = ["Magician 🧝","Witch 🧙"]
In = input('\nEnter Your Gender In Words To Predict Ur Gene - ')
if (In=='Male' or In=='male'):
    print("\nU Must Be An {}! By Ur Gene".format(Box[0]))
elif (In=='Female' or In=='female'):
    print("\nU Must Be An {}! By Ur Gene".format(Box[1]))
else :
    print("\nEnter A Valid Data")
```

Q37. Write a code to access the word "iNeuron" from the given list.

lst = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]



Q38. Take a list as an input from the user and find the length of the list.

Q39. Add the word "Big" in the 3rd index of the given list.

lst = ["Welcome", "to", "Data", "course"]

Q40. What is a tuple? How is it different from list?

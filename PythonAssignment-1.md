## Assignment Part-1
 Q1. Why do we call Python as a general purpose and high-level programming language?

A. Python programming language is not created for solving specific problem but by using the python programming language we can write different variety of programs and we call it as high level because what we write everything will be in readable format.

Ex: Human write the program logic in human readable format.

Q2. Why is Python called a dynamically typed language?

A. The type of variable is determining during only runtime.


Q3. List some pros and cons of Python programming language?

   A. pros:

1. Easy to learn and use
2. Python increases the productivity
3. It is very flexible
4. It has a very supportive community.
        
      Cons:

1. Python is a time-consuming language. It has a low execution speed
2. There are many issues with the design of the language, which only gets displayed during runtime
3. It is not suited for memory-intensive programs and mobile applications
4. Python has a very high memory consumption
    


Q4. In what all domains can we use Python?
   
A. Data science, Data engineer, artificial intelligence, machine learning, web developer


Q5. What are variable and how can we declare them?

  A. Integer, float, string, Boolean

      


value_int=10
print(value_int)

Name_str="Sainath"
print(Name_str)

values_float=55/2
print(values_float)

     
     We can declare variables using the alphabets or by using only one special symbol called as underscore (_)


Q6. How can we take an input from the user in Python?
  
A. We can take the input from the user by using the input() function


name=input('Please enter your name')
print(name)



Q7. What is the default datatype of the value that has been taken as an input using input() function?

A. String


Q8. What is type casting?

A. Converting the variable data type into another data type in order to operation required by the users


Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
 
A. Yes, we can take more than one input from the user by using the split () method.
  

Boys, Girls= input("Enter two values").split()
print("number of Boys = ",Boys)
print("number of Girls = ",Girls)



Q10. What are keywords?
   
A. Keywords have specific meaning and purpose that can be used only for special purposes as they convey the specific message. There are many keywords in every programming language like if,else,elif,break,continue,and,not,or.


Q11. Can we use keywords as a variable? Support your answer with reason.

A. No, we cannot use the keywords as a variables because keywords are predefined in programming language and they have specific meaning so that we cannot use the keyword as a variable


Q12. What is indentation? What's the use of indentaion in Python?

A. Indentation means a space before a code of line

If 1>2:
   Print(‘Yes one is greater than 2 ’)

USE : To indicate a block of code


Q13. How can we throw some output in Python?
 
A. We can throw the output by using the print() function.

Print(“i_Neuron_Bootcamp_2.0”) or we can use single quotation print(‘’)

Q14. What are operators in Python?
A. Operators are used to perform the operations on the variable and values



Q15. What is difference between / and // operators?

A. / means float division and // means int division


Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
   Name_str = ‘iNeuron’*4
   Print(Name_str) 


Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

A. value=int(input("please enter your value : ")) 
B. if value/2:
C.     print("enterd number is even : ")
D. else:
E.     print("entered number is odd : ")


Q18. What are boolean operator?

A. Boolean operator are true and false they will give the output depending on the condition
If given condition is true then it return true

v=10
if v==10:
    print(bool(v))



Q19. What will the output of the following?
```
1 or 0   -> true

0 and 0  -> false

True and False and True -> false

1 or 0 or 0 -> true
```

Q20. What are conditional statements in Python?


A. conditional statement as the name suggests itself, is used to handle conditions in your program. These statements guide the program while making decisions based on the conditions encountered by the program.

Q21. What is use of 'if', 'elif' and 'else' keywords?

A. If-elif-else statement is used in Python for decision-making i.e the program will check the condition and will execute the remaining statements only if the given condition turns out to be true


Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

A.  

age=int(input("Enter your age"))
if age>=18:
 print("your are eligible to vote !")   
else:
 print("your are not eligible to vote !")



Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
# list of numbers
numbers = [12, 75, 150, 180, 145, 525, 50]
 
# iterating each number in list
for num in numbers:
 
    # checking condition
    if num % 2 == 0:
        print(num)


Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

num1,num2,num3=input("please enter three number to find the greatest number ").split()
if num1>num2 and num1>num3:
    print("your greatest number is : ",num1)
elif num2>num1 and num2>num3:
    print("your greatest number is : ",num2)
else:
    print("your greatest numbner is :",num3)



Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```

A. numbers = [12, 75, 150, 180, 145, 525, 50]
for num in numbers:
        if num%5==0:
                if num>=150:
                        continue
                elif num>500:
                        break
                print(num)


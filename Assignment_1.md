#  Assignment - 1
1. In the below elements which of them are values or an expression? eg:- values can be
   integer or string and expressions will be mathematical operators.
  
  * , 'hello', -87.8 , - , / , + ,6
 
Ans: There are total of 4 operators and 3 expressions 
     oprators : * , - , / , +
     expressions : 'hello' , -87.8 , 62. What is the difference between string and variable?

Ans: A variable used to store a information , and a string is a type of information you would stoore in a variable. A   string is a group of characters or a single characters usually enclosed in double quotes " " or single quotes ' ' 3. Describe three different data types.

Ans: there are datatyes in python are integer(int) , float , string

1. int data type : 
       we can use int data type to represent whole numbers.
       ex : int_n = 87
2. float data type :
       we can use float data type of represent floating point values (decimal values)
       ex : flot_n = 87.77 
3. string data type :
       A string is a collaction of one or more characters put in single quote, double quote or triple quote.
       ex : var1 = 'hello world' 4. What is an expression made up of? What do all expressions do?

Ans: An expression is a combination of values , variables , opreators , and calls to functions. expressions need to be evaluated. if we ask python to print an exression , the iterpreter evaluates the expression and displays the result.

```python
2*2+4-8
```




    0


5. This assignment statements, like spam = 10. What is the difference between an
expression and a statement?

Ans: An expression is a combination of values, variables, and operators. when we type an expression at the prompt, the interpreter evaluates it, which means that it finds the value of the expression.
 



```python
2*2+4-8 #is an example of a statement 
```




    0


A statement is a unit of code that has an effect , like creating a variable or displaying a value. when we type a statement, the interpreter executes it , which means that it does whatever the statement says. in general, statement don't have values

```python
2*2+4-8
i = 'samir saiyed'
print("hello world")# is a expression statement
```

    hello world
    
6. After running the following code, what does the variable bacon contain?
bacon = 22
bacon + 1

Ans: The varible bacon is set of 22. the expression bacon+1 does not ressign the value in bacon 

```python
#example_1
bacon = 22 
bacon+1
print(bacon)
```

    22
    


```python
#example_2
bacon = 22
bacon = bacon+1
print(bacon)
```

    23
    
7. What should the values of the following two terms be?
'spam' + 'spamspam'
'spam'*3

Ans: Both expression evalute to the string 'spamspamspam' where as the first expression follow string concatention and the second expression followa string multiplication

```python
print('spam'+'spamspam')
print('spam'*3)
```

    spamspamspam
    spamspamspam
    
8. Why is eggs a valid variable name while 100 is invalid?

Ans: As per python, variable names cannot begin with a number. the python rules for naming a variable are :

1. Variable name must start with a letter or the underscore character.
2. Variable name cannot start with a number.
3. Variable name can only contain alpha-numeric characters and underscore(A-z,0-9,&_).
4. Variable names are case sensitive.
5. The reserved words cannot be used naming the varible.

```python
egg = 'Ineuron'
100 = 'hello'
print(egg)
print(100)
```


      File "C:\Users\SAMIRS~1\AppData\Local\Temp/ipykernel_4968/3041662867.py", line 2
        100 = 'hello'
        ^
    SyntaxError: cannot assign to literal
    

9. What three functions can be used to get the integer, floating-point number, or string
version of a value?

Ans: The int(),float(),and str() functions will evalute to the integer , floating-point number , string version of the value passed to them.

```python
#example:
print('int(10.0)->',int(10.0))
print('float(10)->',float(10.0))
print('str(10)->',str(10.0))
```

    int(10.0)-> 10
    float(10)-> 10.0
    str(10)-> 10.0
    
10. Why does this expression cause an error? How can you fix it?
'I have eaten' + 99 + 'burritos.'

Ans: This cause of error is 99.because 99 is not a string.99 must be typecasted to a string to fix this error. the correct way is : (in example)

```python
#Example :
print('I have eaten'+str(99)+'burritos')
```

    I have eaten99burritos
    

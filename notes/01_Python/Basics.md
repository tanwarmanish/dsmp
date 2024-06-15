#### Notebook: 01_Python
# Why Python?
- Simple to read & Write
- A lot of inbuilt features
- General Purpose
- Vast libraries & community
# Why for Data Science?
- Easy to learn
- Proximity with Maths
- Vast Community
# print
``` Python
print("String Here")
print("Hello", "World")
print("Hello","World",sep="/")
print("Hello",end="-")
print("World")
```
# Data Types
## 1. Integer
- Max 10e309 - 1
``` Python
print(12)
```
## 2. Float
- Max 1e309
``` Python
print(3.14)
```
## 3. String
``` Python
print('Hello World')
```
## 4. Complex
``` Python
print( 5 + 6j )
```
## 5. List
``` Python
print([1,2,3,4,5])
```
## 6. Tuple
``` Python
print((1,2,3,4,5))
```
## 7. Sets
``` Python
print({1,2,3,4,5})
```
## 8. Dictionary
``` Python
print({"first":1,"second":"Second"})
```
# Variables
- To container to store data
- It supports **Dynamic Typing** i.e. no need to declare the variables
- It supports **Dynamic Binding** i.e. data type of a variable can change.
``` Python
var_name = value
print(var_name)

a,b,c = 1,2,3

a=b=c=5
```
# Comments
``` Python
# Single Line Comment

'''
Multi 
Line
Comment
'''
```
# Keywords
- Reserved words that can not be used for variable names.
- There are 32 Keywords in Python
``` Python
helps() -> keywords
```
# Identifiers
- The name we give to identify a variable, function, class, module or other object.
- Rules:
	- Cannot start with a **Digit**
	- Allowed Special Character -> _ (Underscore)
	- Cannot be a Keyword
# input
- Input values are in string always
``` Python
input_value = input("Message Here :")
```
# type
- Returns data type of a given variable
``` Python
type(var_name)
```
# Type Conversion
It is of two types:
1. Implicit -> Automatic by Python
2. Explicit -> Manual by Dev
``` Python
# Implicit
print( 5 + 5.6 )

# Explicit
number = int(input("Enter Number :"))
print( number * 10 )

str(number)
float(number)
bool(number)
```
# Literals
- A constant value that is assigned to the variable
``` Python
# Binary Literal
a = ob1010

# Decimal Literal
b = 100

# Octal Literal
c = 0o310

# Hexadecimal Literal
d = 0x12c

# Float Literal
f = 10.5
f = 1.5e2
f = 1.5e-3

# Complex Literal
x = 5 + 6j
print( x.real )
print( x.imag )

# String Literal
str1 = 'This is String'
str2 = "This is String"
multiline_string = """Thi is a string"""
unicode_string = u"\..."
raw_string = r"raw \n string"

# Bool -> Number
# True -> 1, False -> 0
print( True + 4 ) # 5
```
# None
- The None keyword is used to define a null value, or no value at all.
- It can be used to declare variables
``` Python
a = None
# Some Code Here
a = 10
```


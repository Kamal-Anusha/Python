# Python

python --version
py
python Anusha.py
print("Hello, World!")
x='10
y='test'
comment--####
casting
x=str(3), float(3), int(3)
type(x)
Python its a case-sensitive
Variables start with letter or underscore, case-sensitive, can only contain alpha-numeric and underscore, cannot start with a number
Multi Word Variable  - Camle case, Pascal Case, Snake Case ---> my_variable
Multi Values to Multi Variables --> x, y, z = "Orange", "Banana", "Cherry"
x = y = z = "Orange"
If you have a collection of values in a list, tuple etc. Python allows you to extract the values into variables. This is called unpacking.
fruits = ["apple", "banana", "cherry"]
x, y, z = fruits
Tuples are used to store multiple items in a single variable. Can also use function tuple((1,2,3))
Global Variables - Variables that are created outside of a function are known as global variables
x = "awesome"

def myfunc():
  print("Python is " + x)

myfunc() 
------------
x = "awesome"

def myfunc():
  x = "fantastic"
  print("Python is " + x)

myfunc()
--------------
Defining global variable inside a function
def myfunc():
  global x
  x = "fantastic"

myfunc()

print("Python is " + x)
------------------
Changing gobal variable inside a function
x = "awesome"

def myfunc():
  global x
  x = "fantastic"

myfunc()

print("Python is " + x) 
-----------------
Text Type: 	str
Numeric Types: 	int, float, complex
Sequence Types: 	list, tuple, range
Mapping Type: 	dict
Set Types: 	set, frozenset
Boolean Type: 	bool
Binary Types: 	bytes, bytearray, memoryview
None Type: 	NoneType
-----------------
***Data Types - https://www.w3schools.com/python/python_datatypes.asp

Int, or integer, is a whole number, positive or negative, without decimals, of unlimited length
Float, or "floating point number" is a number, positive or negative, containing one or more decimals
Float can also be scientific numbers with an "e" to indicate the power of 10
Complex numbers are written with a "j" as the imaginary part:
x = 3+5j

Random Number

Python does not have a random() function to make a random number, but Python has a built-in module called random that can be used to make random numbers:
import random

print(random.randrange(1, 10)) 

-----------------
Python Casting
y = int(2.8) # y will be 2
y = float(2.8)   # y will be 2.8
z = str(3.0)  # z will be '3.0'

-----------------

'hello' is the same as "hello"
Multiline Strings
You can assign a multiline string to a variable by using three double quotes Or three single quotes:
a = """Lorem ipsum dolor sit amet,
consectetur adipiscing elit,
sed do eiusmod tempor incididunt
ut labore et dolore magna aliqua."""
print(a) 


Strings are Arrays

a = "Hello, World!"
print(a[1])

Looping Through a String

for x in "banana":
  print(x)
  
String Length

a = "Hello, World!"
print(len(a))

**Check String
txt = "The best things in life are free!"
print("free" in txt)

txt = "The best things in life are free!"
if "free" in txt:
  print("Yes, 'free' is present.")
  
Check if NOT

txt = "The best things in life are free!"
if "expensive" not in txt:
  print("No, 'expensive' is NOT present.")
  
Slicing
b = "Hello, World!"
print(b[2:5])

b = "Hello, World!"
print(b[:5])

b = "Hello, World!"
print(b[2:])

b = "Hello, World!"
print(b[-5:-2])

Upper Case
a = "Hello, World!"
print(a.upper())

Lower Case
a = "Hello, World!"
print(a.lower())

Remove Whitespace
a = " Hello, World! "
print(a.strip()) # returns "Hello, World!" 

Replace String
a = "Hello, World!"
print(a.replace("H", "J"))

Split String
a = "Hello, World!"
print(a.split(",")) # returns ['Hello', ' World!'] 

String Methods
String Concatenation
a = "Hello"
b = "World"
c = a + " " + b
print(c)

String Format
age = 36
txt = "My name is John, and I am {}"
print(txt.format(age))


quantity = 3
itemno = 567
price = 49.95
myorder = "I want {} pieces of item {} for {} dollars."
print(myorder.format(quantity, itemno, price))

quantity = 3
itemno = 567
price = 49.95
myorder = "I want to pay {2} dollars for {0} pieces of item {1}."
print(myorder.format(quantity, itemno, price))

Escape Characters - https://www.w3schools.com/python/python_strings_escape.asp
\", \', \\, \n, \t, \b, \r, \f

String Methods:https://www.w3schools.com/python/python_strings_methods.asp
String Methods

Boolean Values
print(10 > 9)
print(10 == 9)
print(10 < 9)

a = 200
b = 33

if b > a:
  print("b is greater than a")
else:
  print("b is not greater than a") 
  
x = "Hello"
y = 15

print(bool(x))
print(bool(y))

Most Values are True

Almost any value is evaluated to True if it has some sort of content.

Any string is True, except empty strings.

Any number is True, except 0.

Any list, tuple, set, and dictionary are True, except empty ones.

bool("abc")
bool(123)
bool(["apple", "cherry", "banana"])

Some Values are False
bool(False)
bool(None)
bool(0)
bool("")
bool(())
bool([])
bool({}) 

One more value, or object in this case, evaluates to False, and that is if you have an object that is made from a class with a __len__ function that returns 0 or False: 
class myclass():
  def __len__(self):
    return 0

myobj = myclass()
print(bool(myobj)) 
def myFunction() :
  return True

if myFunction():
  print("YES!")
else:
  print("NO!") 
 
Python also has many built-in functions that return a boolean value, like the isinstance() function, which can be used to determine if an object is of a certain data type:

x = 200
print(isinstance(x, int)) 

------------------------
Python Operators
Python divides the operators in the following groups:

    Arithmetic operators
    Assignment operators
    Comparison operators
    Logical operators
    Identity operators
    Membership operators
    Bitwise operators
Python Arithmetic Operators
+,-,/,*,%,**,//

Python Assignment Operators



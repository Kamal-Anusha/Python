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



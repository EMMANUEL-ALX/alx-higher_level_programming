Solution to tasks on 0x05. Python - Exceptions
Task 0: Safe list printing
Write a function that prints x elements of a list.

Prototype: def safeprint list(mylist=[], x=0):
mylist can contain any type (integer, string, etc.)
All elements must be printed on the same line followed by a new line.
x represents the number of elements to print
x can be bigger than the length of my list
Returns the real number of elements printed
You have to use try: / except:
You are not allowed to import any module
You are not allowed to use len()
Task 1. Safe printing of an integers list
Write a function that prints an integer with "{:d}".format().

Prototype: def safe print integer(value):
value can be any type (integer, string, etc.)
The integer should be printed followed by a new line
Returns True if value has been correctly printed (it means the value is an integer)
Otherwise, returns False
You have to use try: / except:
You have to use "{:d}".format() to print as integer
You are not allowed to import any module
You are not allowed to use type()

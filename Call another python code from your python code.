#!/bin/python
#import os package to use it for calling the other code or any system request.
import os

#import time since we will make the code sleep for some amount of seconds.
import time

# The code will call another python code that accepts two arguments.
# In this code we will call the other code with fixed first argument & loop the second arguments as X variable.

x = 0
while x < 500:	
	z = os.system("python3 MysecondCode.py Arg1.txt %s "%x)
	time.sleep(1)
	x=x+1

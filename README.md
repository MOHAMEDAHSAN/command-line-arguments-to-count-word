# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys module
### Step 2: 
Establish a file connection between an already existing text file
### Step 3: 
Define any variable an split() the read() content from the text file (ie), the word count
### Step 4:  
Display the word count variable using print()
## PROGRAM:
~~~Python
import sys
f=open(sys.argv[1],'r')
a=f.read().split()
print('Words : ',len(a))
~~~
## OUTPUT:
![output](/op.png)
#### Text File :
![txt](/txt.png)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.

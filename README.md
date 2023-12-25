# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a text file in a specific loaction of interest.
### Step 2: 
 On the same location as the text file, create a python program file.
### Step 3: 
In python Program, import sys and open a text file with argument "sys.argv[1]"
### Step 4:  
using read() and split(), split the lines in the file into a sequence of words.
### Step 5: 
using len() count the number of words in the text file.
### Step 6: 
In command prompt, initiate python followed by program name and text file name to get the output.
## PROGRAM:
```
'''
Developed by RAMESH RENUKA
Registered number: 212223240136
'''
import sys
file= open(sys.argv[1])
data=file.read()
words=data.split()
print("Total Words:",len(words))
```
### OUTPUT:
![image](https://github.com/MOHAMEDFAROOK2005/command-line-arguments-to-count-word/assets/150319482/0c2483e4-9bcc-4a7e-a3a2-a3e7390b69a2)
![image](https://github.com/MOHAMEDFAROOK2005/command-line-arguments-to-count-word/assets/150319482/71004c3e-6304-45d5-8eef-f7d5b9a8eef7)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.

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
Developed by Dhandeeswaran selvakumar
Registered number: 23006838
'''
import sys
file= open(sys.argv[1])
data=file.read()
words=data.split()
print("Total Words:",len(words))
```
### OUTPUT:
![Screenshot 2023-12-27 154153](https://github.com/dhandeeswaran2005/command-line-arguments-to-count-word/assets/147139188/c8855575-dd14-4ee3-a27a-6f214752d800)
![Screenshot 2023-12-27 154201](https://github.com/dhandeeswaran2005/command-line-arguments-to-count-word/assets/147139188/fd20a956-0da1-4bd5-964a-7979f68cd772)
![Screenshot 2023-12-27 154208](https://github.com/dhandeeswaran2005/command-line-arguments-to-count-word/assets/147139188/71e30968-e8e6-41d7-92b7-d1a24794afc5)




## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.

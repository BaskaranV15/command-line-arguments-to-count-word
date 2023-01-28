# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys package
### Step 2: 
Create an empty dictionary
### Step 3: 
Open the text file in read mode
### Step 4:  
Split words in each line and store in list
### Step 5: 
Count the number of occurence of each word in the list
### Step:
Count the number of occurence of each word in the list
## PROGRAM:
```
import sys
fp = open(sys.argv[1],"r")
d={}
for i in fp:
    for w in i.split():
        if w not in d.keys():
            d[w] = 1
        else:
            d[w] += 1
print(d)

```
### OUTPUT:
![output](linearg.png)
## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.

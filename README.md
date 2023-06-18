# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: Import sys

### Step 2: Pass the filename as the first argument after the name of script. Open the file as sys.argv[1]
 
### Step 3: Read the file using read() method.

### Step 4: Use split() method to split the file content into words.. 

### Step 5: Use len() to find the total words.

### Step 6: Use len() to find the total words.

## PROGRAM:
```
#Program for getting word count from the contents of a file using command line arguments.
#Developed by: Tharika S
#RegisterNumber: 2122222230159

import sys
with open(sys.argv[1],'r') as f:
    num_of_words =0
    for i in f:
        word =i.split()
        num_of_words += len(word)
print("Number of words={}".format(num_of_words))
```

### OUTPUT:
![image](https://github.com/tharikasankar/command-line-arguments-to-count-word/assets/119475507/28575e90-5be3-4c99-bd1b-d51e4b55824f)

![image](https://github.com/tharikasankar/command-line-arguments-to-count-word/assets/119475507/3007feb9-98cd-4311-9fa4-3d5e5fd2f7e4)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.

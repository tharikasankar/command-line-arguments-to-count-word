# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: Import sys

### Step 2: Open file using commandline arguments.
 
### Step 3: Using for loop find the word count from the contents of a file.

### Step 4: Use len to count number of words. 

### Step 5: Give print statement.

### Step 6: End the program.

## PROGRAM:
```
#Developed by:Tharika S
#Register num: 212222230159
import sys
count = 0
with open(sys.srgv[0],'r) as f:
    for line in f:
        word = line,split()
        count+= len(word)
print("Word count in File = ",count)   
```

### OUTPUT:
![image](https://github.com/tharikasankar/command-line-arguments-to-count-word/assets/119475507/28575e90-5be3-4c99-bd1b-d51e4b55824f)

![image](https://github.com/tharikasankar/command-line-arguments-to-count-word/assets/119475507/3007feb9-98cd-4311-9fa4-3d5e5fd2f7e4)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.

# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: Import sys

### Step 2: Open file using open().

### Step 3: Use for loop

### Step 4: Use len to count number of words.

### Step 5: Print the word count using the print statement

### Step 6: End of the program.

## PROGRAM:
```python
#Developed by: S.Shanmathi
#RegisterNumber: 22003171
import sys
count= 0
with open(sys.argv[1],'r') as f1:
    for line in f1:
        word= line.split()
        count += len(word)
print("word count in file = ",count)
```

### OUTPUT:
![5b](https://user-images.githubusercontent.com/121243595/215336625-cc8474db-2824-42f6-ad5d-fee78deff5c8.jpg)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.

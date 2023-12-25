# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
## Step 1: Import the sys module
## Step 2: Pass the filename as the first argument after the name of script. Open the file as sys.argv[1]
## Step 3: Read the file using read() method.
## Step 4: Use split() method to split the file content into words.
## Step 5: Use len() to find the total words.
## Step 6: Run the program to determine the number of words in the file created.
## PROGRAM:
```
Python program for getting the word count from the contents of a file using command line arguments.
Developed by: M HIMAVATH
RegisterNumber: 23010121

import sys
count = 0
with open (sys.argv[1],'r') as f1:
    for line in f1:
        word = line.split()
        count += len (word)
print("word count in file = ",count)
```
### OUTPUT:
![256272881-2861dff3-5f6b-472a-96f0-c3868fff92de](https://github.com/Himavath08/command-line-arguments-to-count-word/assets/139110631/f715f313-abcb-4608-861f-040639945157)

![256272037-d261e11e-e107-4dde-b93e-8510d2783864](https://github.com/Himavath08/command-line-arguments-to-count-word/assets/139110631/b2b6018b-94cf-4a97-8199-5217d844b7dc)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.

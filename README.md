# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open Jupyterlab and a plain text file and save the file.

### Step 2:
Create python notebook.
 
### Step 3:
Open the plain text file using open().


### Step 4:
Using for loop find the word count of the plain text file.


### Step 5: 
Display the word count of the plain text file

### Step 6:
Stop the python notebook.


## PROGRAM:
Name: C Saravanan
Register Number: 22008175
num_word=0
with open("try5.txt","r")as f:
    for i in f:
        word=i.split()
        num_word+=len(word)
print("The Number of words in the file is {}".format(num_word))



### OUTPUT:

## RESULT:
Thus the program is written to find the word count from a text.

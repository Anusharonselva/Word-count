# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:Create a file object and get file name from the user
### Step 2: Open the file given by the user
### Step 3: Using for loop access the file
### Step 4: Use split funtion to separate the words
### Step 5: The words is then counted by len function
### Step 6: Print the number of words

## PROGRAM:
'''
Program to count the number of words in a file

Developed by : S.ANUSHARON

Register number: 212222240010

num=0

with open("file1.txt","r") as f1:

    for i in f1:
    
        word=i.split()
        
        num += len(word)
        
print("The number of words are in the file is ",num)

'''

### OUTPUT:

![Screenshot (325)](https://github.com/Anusharonselva/Word-count/assets/119405600/10f98109-6d5d-4a94-a6f6-bfbd46da2276)


## RESULT:
Thus the program is written to find the word count from a text.

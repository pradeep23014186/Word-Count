# Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import numpy as np

### Step 2: 
Enter the input values
 
### Step 3: 
Write python program for getting the word count from the contents of a file using command line arguments

### Step 4:  
Run the program

### Step 5: 
Input the values

### Step 6: 
End the program

## PROGRAM:
```
program to find the number of words in a text file
Developed by : Pradeep Kumar.G
Register number : 212223230150
```
```
num=0
with open("story.txt","r") as f1:
    for i in f1:
        word=i.split()
        num += len(word)
print("The number of words are in the file is ",num)
```
### OUTPUT:
![Screenshot 2024-05-14 162313](https://github.com/pradeep23014186/Word-Count/assets/152294642/3e6eb29f-5c2a-48ea-a2d5-ff617fbf6e78)

![image](https://github.com/KrishnaPrasad148/Word-Count/assets/147332763/9bae16e6-61e3-41b2-9ef7-18a586da7910)


## RESULT:
Thus the program is written to find the word count from a text.

# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Start the program.
### Step 2: 
 Give the input string.
### Step 3: 
Print the original string.
### Step 4:  
using len(test_string.split()) get the result.
### Step 5: 
Print the word count.
### Step 6: 
End the program.
## PROGRAM:
```python
#python program for word count
#Developed by : RIYA P L
#Reference no : 23005672

def wordcount(filename):
count=0
with open(filename,"r") as f:
for data in f:
words=data.split()
for word in words:
count+=1
print("Total number of words:",count)
filename=input("Enter Filename:")
wordcount(filename)
```

### OUTPUT:
<img width="569" alt="word1" src="https://github.com/23005672/Word-count/assets/138971519/bf8ac0e1-9e91-4cbc-b12e-9061f9c97d73">
<img width="548" alt="word2" src="https://github.com/23005672/Word-count/assets/138971519/d4c05b9b-175f-4d9d-949c-3b2ddadac881">



## RESULT:
Thus the program is written to find the word count from a text.

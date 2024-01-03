# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
create a text file using jupyter
### Step 2: 
 now open the text file sample.txt
### Step 3: 
to open use with open() function
### Step 4:  
now to count split the text by giving split()
### Step 5: 
give for loop to count
### Step 6: 
by now it gets added and gives output
## PROGRAM:
```
#Program to find the Word Count
#Developed by : Allen Joveth P
#Register Number : 23009582
num=0
with open("sample.txt","r") as f1:
    for i in f1:
        word=i.split()
        num +=len(word)
print("The number of words are in the file is ",num)
```
### OUTPUT:

![Screenshot 2024-01-03 165020](https://github.com/allenjoveth/Word-count/assets/139422287/6ace0c67-bdfc-4916-8d65-95c1b194e90a)


## RESULT:
Thus the program is written to find the word count from a text.

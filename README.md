# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: open the file with a with open method 

### Step 2: open in r+ type
 
### Step 3: create a for loop in sentence

### Step 4:  using split() split the word

### Step 5: ia variable count the len splited word 

### Step 6: print count

## PROGRAM:
 
# program to find the word count 
# Developed by : Sanjay siavaramakrishnan M
# Regester number: 23013798

with open(r"C:\Users\admin\OneDrive\for python\py\file.py\sanjay.txt",'r+') as sentence :<br>
    count=0<br>
    for x in sentence:<br>
        word=x.split()<br>
        count+=len(word)<br>
print(count)<br>
 

### OUTPUT:

![image](https://github.com/sanjaysivaramakrishnan/Word-count/assets/151629616/acd9b215-efaf-4106-8c21-2191c1360123)



## RESULT:
Thus the program is written to find the word count from a text.

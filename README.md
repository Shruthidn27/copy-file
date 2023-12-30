# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a text1.txt with some content in it
### Step 2:
Open the text1.txt file in read mode
### Step 3:
Create a copy.txt file using write mode
### Step 4:
Copy the content of text1.txt file to copy.txt using write function
## PROGRAM:
```
Program for copying the contents from one file to another file
Developed by: Shruthi D.N
Register Number: 23010231

with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)
```
### OUTPUT:
![image](https://github.com/Shruthidn27/copy-file/assets/138849783/ef8327ee-ca2e-4400-868e-ea5cd91f67a1)

## RESULT:
Thus the program is written to copy the contents from one file to another file.

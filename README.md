# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open a file named java.txt in read mode.
### Step 2: 
 data= f1.raed() this statement reads the entire data of the file.
### Step 3: 
Open a new file(copyjava.txt) to copy your existing file.
### Step 4:  
Open a file named copyjava.txt in writing mode.
### Step 5: 
f2.write(data) this statement enables you to write the content read in existing file into your new file.

## PROGRAM:
```
with open("java.txt","r") as f1:
    data = f1.read()
with open("copyjava.txt","w") as f2:
    f2.write(data)
```

### OUTPUT:

![Output](./copyop.png)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
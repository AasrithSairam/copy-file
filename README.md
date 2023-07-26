# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:  Create a text1.txt with some content in it

### Step 2: Open the text1.txt file in read mode
 
### Step 3: Create a copy.txt file using write mode

### Step 4: Copy the content of text1.txt file to copy.txt using write function

## PROGRAM:
```
#Program for copying the contents from one file to another file
#Programmed By: ponguru aasrith sairam
#RegisterNumber: 23007809

with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)
```

### OUTPUT:
![image](https://github.com/AasrithSairam/copy-file/assets/139331438/0760e043-c34a-41ad-9199-947903a8cd4b)
![image](https://github.com/AasrithSairam/copy-file/assets/139331438/c0c0f8db-f8f4-411b-bfea-c43185615dde)
![image](https://github.com/AasrithSairam/copy-file/assets/139331438/86883382-968c-4e14-8729-1b71c7705997)






## RESULT:
Thus the program is written to copy the contents from one file to another file.

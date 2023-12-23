# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
# Step 1:
Create a text1.txt with some content in it

# Step 2:
Open the text1.txt file in read mode

# Step 3:
Create a copy.txt file using write mode

# Step 4:
Copy the content of text1.txt file to copy.txt using write function: 

## PROGRAM:
```
Program for copying the contents from one file to another file
Developed by:Lokhnath J
RegisterNumber: 23004865

with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)
```
### OUTPUT:
![image](https://github.com/Lokhnath10/copy-file/assets/138969918/6c69c2c3-ac5d-4227-95b6-060a2f137e64)
![image](https://github.com/Lokhnath10/copy-file/assets/138969918/9e812f9d-1232-430a-bcb9-f5218c470ba3)
![image](https://github.com/Lokhnath10/copy-file/assets/138969918/29a3df75-1292-4a6f-b773-37db18777d00)


## RESULT:
Thus the program is written to copy the contents from one file to another file.

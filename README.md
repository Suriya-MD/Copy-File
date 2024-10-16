## Date:
# Exp-11: Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: Define the function as copy with arguements as existing file name and new file name.

### Step 2: Open the existing file to read.
 
### Step 3: Open the new file to write.

### Step 4:  Copy the contents from existing file to new file.

### Step 5: Get the inputs from the user for existing file and new file. Call the function.

### Step 6: End the program.
 

## PROGRAM:
```
##Developed By: SURIYA M
##Reg No: 212223110055

def copy_file(source_file, destination_file):
    with open(source_file, 'r') as src:
        with open(destination_file, 'w') as dest:
            dest.write(src.read())

source = 'Text_file.txt'  
destination = 'Empty_file.txt'
copy_file(source, destination)

print(f"Contents copied from {source} to {destination}.")


```
### OUTPUT:

![image](https://github.com/user-attachments/assets/7f22289a-1fc4-4682-9c83-c2018bc843f4)
![image](https://github.com/user-attachments/assets/4497eacd-87b0-482e-af8c-2f00f8330c9c)
![image](https://github.com/user-attachments/assets/ee96e8d8-ae99-4e0d-bef1-f8f8defa6c0a)


## RESULT:
Thus the program is written to copy the contents from one file to another file.

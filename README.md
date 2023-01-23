# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the required file by using the function "with" in read mode.
### Step 2: 
Open the another required file by using the function "with" in append mode to append.
### Step 3: 
Use for loop in file1.
### Step 4:  
Use write function.
### Step 5: 
To write the file 1 content in file 2.
### Step 6: 
End the program.


## PROGRAM:

with open('sample.txt','r') as file1:
    with open ('san1.txt','a') as file2:
        for line in file1:
            file2.write(line)


### OUTPUT:
![copyfile](https://user-images.githubusercontent.com/120620842/214024001-d3f83615-bc66-42f6-80ff-2762b272cbc9.jpg)
![copyfile2](https://user-images.githubusercontent.com/120620842/214024046-14e2f547-d7ce-4406-9991-12228d7ebdec.jpg)



## RESULT:
Thus the program is written to copy the contents from one file to another file.

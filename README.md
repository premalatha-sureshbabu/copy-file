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
```

program developed by:premalatha.s
registration number:22009393 
with open("file.txt") as fp:
    with open("fire2.txt","w") as fp1:
        line= fp.read()
        fp1.write(line)
        
 ```     
       
        

### OUTPUT:

![Screenshot (71)](https://user-images.githubusercontent.com/120620842/214801508-e14ed0eb-c5e4-4e37-a4ea-8dac8e898df7.png)


## RESULT:
Thus the program is written to copy the contents from one file to another file.

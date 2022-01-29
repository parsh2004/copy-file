# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
# Step 1:
Create a text file with some written information

# Step 2:
Open the text file with open()

# Step 3:
Open the empty text file to copy the information

# Step 4:
By using the function write() copy the text written in the file1 to file2.

# Step 5:
End the program

# PROGRAM:
~~~
#Developed by:parsh
with open("text1.txt") as f:
    with open("text2.txt", "w") as f1:
        for line in f:
            f1.write(line) 
~~~

### OUTPUT:
![github](type.png)
![github](text1.png)
![github](text2.png)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
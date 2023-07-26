# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the source file in read mode.

### Step 2: 
Read the contents of the source file and store it in a variable
### Step 3: 
Close the source file.
### Step 4:  
Open the destination file in write mode. If the file doesn't exist, it will be created.
### Step 5: 
Write the contents from the variable to the destination file.
### Step 6: 
Read the contents of the destination file and print it to verify the copy operation.
### Step 7:
End the program
## PROGRAM:
~~~python
#Program to copy the text from one file to another
#Developed by :Meenu.S
#Register umber : 23003303
f=open(r"/content/drive/My Drive/example_file.txt","r")
a=f.read()
print(a)
b=open(r"/content/drive/My Drive/copied_file.txt","w+")
b.write(a)
b.seek(0)
print(b.read())

~~~

### OUTPUT:
![Alt text](<python 5c.png>)
![Alt text](<5c eg.png>)
![Alt text](<5c co.png>)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
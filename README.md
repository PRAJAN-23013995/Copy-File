# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1:
Open a Existing file with read mode.

Step 2:
Create a new file without closing the existing file.

Step 3:
Read the data from existing file.

Step 4:
Write the readed data in created new file.

Step 5:
Close both the file pointers

Step 6:
End the program.

## PROGRAM:
Developed by: PRAJAN P
Register number: 212223240121
```
def copy(fname,newfile):
    with open(fname) as fp:
        with open(newfile,'w') as fp1:
            data=fp.read()
            fp1.write(data)
copy('Myfile.txt','file1.txt')
```
### OUTPUT:
![output](https://github.com/PRAJAN-23013995/Copy-File/assets/150313345/8e62f72a-7fda-4736-9d5e-31140b95ebf3)

## RESULT:
Thus the program is written to copy the contents from one file to another file.

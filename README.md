# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1:
First we need to open the required file form which we need to copy the text.Again using the with keyword to open the empty file.

Step 2:
Using keyword "with" to open the requied file.

Step 3:
Again using the with keyword to open the empty file.

Step 4:
The empty file is open by using 'W' which is used to write only.

Step 5:
The four function is used to take each line from the main file.

Step 6:
The four function is used to take each line from the main file.

Step 7:
Print the output.
## PROGRAM:
```
#developed by Bejin.B
#ref no:22001908
print("Enter the Name of Source File: ")
sFile = input()
print("Enter the Name of Target File: ")
tFile = input()
fileHandle = open(sFile, "r")
texts = fileHandle.readlines()
fileHandle.close()
fileHandle = open(tFile, "w")
for s in texts:
fileHandle.write(s)
fileHandle.close()
print("\nFile Copied Successfully!")
```
### OUTPUT:

![image](https://user-images.githubusercontent.com/118367518/215099723-2d73252a-2833-4fbd-bb24-c6af0abb5fee.png)

## RESULT:
Thus the program is written to copy the contents from one file to another file.

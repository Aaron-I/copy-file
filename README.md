# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a text file
### Step 2: 
Read the text file 
### Step 3: 
Copy the file using write mode
### Step 4:  
End the program.

## PROGRAM:
    #To copy file
    #Developed by : AARON I
    #Register number : 23002289
```
from google.colab import drive
drive.mount('/content/drive')

with open('/content/drive/My Drive/csv file1.txt','r') as f:
  text=f.read()
with open('/content/drive/My Drive/p1.txt','w') as g:
  g.write(text)
```
### OUTPUT:
![output](/Screenshot%202023-07-26%20144910.png)
![output](/screenshot2.png)
![output](/screenshot3.png)


## RESULT:
Thus the program is written to copy the contents from one file to another file.

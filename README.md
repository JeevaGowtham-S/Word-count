# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
## Step 1:
Open terminal and activate conda, then open jupyter notebook.
<br>

## Step 2:
Create a text file in jupyter notebook or upload a text file in the jupyter notebook.
<br>

## Step 3:
Open a new cell in jupyter notebook.
<br>

## Step 4:
Type the program in the cell.
<br>

## Step 5:
Now in the output box,type the file name.
<br>

## Step 6:
End the program.
<br>

## PROGRAM:
```
#Developed by: JEEVAGOWTHAM S
#Reference No: 220087690
fname=input("Enter file name: ")
num_words=0
with open(fname,'r') as f:
    for line in f:
        words=line.split()
        num_words+=len(words)
print("Number of words: ",num_words)
```
### OUTPUT:
![Screenshot from 2023-01-26 16-22-55](https://user-images.githubusercontent.com/118042624/214818865-6d29edcb-4f68-4018-bbbe-3cc45a979445.png)

TEXT FILE:
![Screenshot from 2023-01-26 16-22-39](https://user-images.githubusercontent.com/118042624/214818929-4a8b3420-f9a0-4319-8f60-98ba153a1ccc.png)




## RESULT:
Thus the program is written to find the word count from a text.

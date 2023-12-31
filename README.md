# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Get the file name as input from the user.
### Step 2: 
Open the specified file in read mode.
### Step 3:
Iterate through each line in the file
### Step 4: 
Split the line into individual words using spaces as separators.
### Step 5:  
Add the number of words in the line to the word count.
### Step 6: 
Print the total number of words found in the file.
 
## PROGRAM:
```
#Progream to find the Word Count using command line aruments
#Developed by: P P PARTHIBAN
#Register Number: 23007965

fname=input("enter the file name")
num_words=0
with open(fname,"r") as f:
    for line in f:
        word=line.split()
        num_words+=len(word)
print("The number of words: ",num_words)
```


### OUTPUT:
![image](https://github.com/23007965/command-line-arguments-to-count-word/assets/138971238/e447b002-d42f-429c-af3a-299e8969375a)

![image](https://github.com/23007965/command-line-arguments-to-count-word/assets/138971238/d65035c8-3878-4b95-a2f7-87786f494773)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.

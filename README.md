# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:Open the file in read mode and handle it in text mode

### Step 2: Read the text using read() function.
 
### Step 3: Split the text using space separator .we assume that words in a sentence are separated by a space character.



### Step 4: The length of the split list should equal the numbe of words in the text file. 

### Step 5: You can refine the count by clearing the string prior t splitting or validatting the words after splitting


## PROGRAM:
```
To write a program for getting the word count from a file.
Developed by: M Srinath
RegisterNumber: 22000990
def wordcount():
    count = 0
    with open("file1.txt",'r') as f:
        a =  f.read()
        for line in a.split():
            count+=1 
    print("number of words in the paragraph are",count)
wordcount()
```
### OUTPUT:
![output](https://user-images.githubusercontent.com/118678482/214656568-4a5ba3ee-ad86-4528-b4b0-4c6800edb8d4.png)





## RESULT:
Thus the program is written to find the word count from a text.

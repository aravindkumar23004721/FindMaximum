# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:

i)	# To find the maximum of marks using the list method sort.
```Python
Program to mark the maximum of marks using the list method sort
Developed by:aravindkumar 
RegisterNumber:23004721 

def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```Python
Program to find the maximum marks using the list method max().
Developed by:aravindkumar 
RegisterNumber:23004721 

def max_marks(marks):
    max1=max(marks)
    return max1
```

iii) # To find the maximum marks without using builtin functions.
```Python
Program to the maximum marks without using builtin functions.
Developed by:aravindkumar 
RegisterNumber:23004721

def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![Screenshot 2023-11-26 214241](https://github.com/aravindkumar23004721/FindMaximum/assets/148962674/ef75fe16-1252-4649-a09a-ef21bd222971)

![Screenshot 2023-11-26 214304](https://github.com/aravindkumar23004721/FindMaximum/assets/148962674/9f6fbc3b-118e-4771-a5f7-db6217d5221a)

![Screenshot 2023-11-26 214341](https://github.com/aravindkumar23004721/FindMaximum/assets/148962674/c7147c40-9586-413e-9200-ad4e35e99893)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.

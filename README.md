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
```
Program to mark the maximum of marks using the list method sort
Developed by:SREEKUMAR S
RegisterNumber:23008070

def max_marks(marks):
    marks.sort()
    return marks[-1]



```

ii)	# To find the maximum marks using the list method max().
```
Program to find the maximum marks using the list method max().
Developed by:SREEKUMAR S
RegisterNumber:23008070

def max_marks(marks):
    a=max(marks)
    return a



```

iii) # To find the maximum marks without using builtin functions.
```
Program to the maximum marks without using builtin functions.
Developed by:SREEKUMAR S
RegisterNumber:23008070

def max_marks(list1):
    a=0
    for i in list1:
        if i>a:
            a=i
    return a


```
## Sample Input and Output
![case 1](https://github.com/guru14789/FindMaximum/assets/151705853/8916cf5b-fd4d-4353-bb3d-a0feaab1299e)
![case2](https://github.com/guru14789/FindMaximum/assets/151705853/40f5cc2c-a793-478b-89f9-2d8cc9c606cc)
![case 3](https://github.com/guru14789/FindMaximum/assets/151705853/a34b85b0-5d12-4930-b57e-706448a61823)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.

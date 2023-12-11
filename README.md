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
Developed by: Tanushree.A
RegisterNumber: 23004953
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large



```

ii)	# To find the maximum marks using the list method max().
```

Program to find the maximum marks using the list method max().
Developed by: Tanushree.A
RegisterNumber: 23004953

def max_marks(marks):
    large=max(marks)
    return large



```

iii) # To find the maximum marks without using builtin functions.
```
Program to the maximum marks without using builtin functions.
Developed by: Tanushree.A
RegisterNumber: 23004953
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max



```
 

## Output:
![3a op 1](https://github.com/Tanug25/FindMaximum/assets/138849166/2359764e-d4e1-49b7-b633-516af1ba62b7)
![3a op 2](https://github.com/Tanug25/FindMaximum/assets/138849166/d7efee29-9caf-41c1-860b-4659020dedac)
![3a op 3](https://github.com/Tanug25/FindMaximum/assets/138849166/765b7103-34cd-436c-93ac-bdf6e575b23a)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.

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
Developed by:Preethi.A.A 
RegisterNumber:22008332 
'''
def max_marks(marks):
    #Write your code here
    marks.sort()
    large = marks[-1]
    return large

```

ii)	# To find the maximum marks using the list method max().
```Python
Program to find the maximum marks using the list method max().
Developed by:Preethi.A.A 
RegisterNumber:22008332 
'''
def max_marks(marks):
    # write your code here
    max = marks[0]
    for x in marks:
        if x > max:
            max = x
    return max

```

iii) # To find the maximum marks without using builtin functions.
```Python
Program to the maximum marks without using builtin functions.
Developed by:Preethi.A.A 
RegisterNumber:22008332 
'''
def max_marks(list1):
    # write your code here
    max=list1[0]
    for number in list1:
        if(number > max):
            max = number
    return max

```
## Output:
![](./Maximum%20in%20a%20list1.png)
![](./Maximum%20in%20a%20list2.png)
![](./Mximum%20in%20a%20list%203.png)

## Result:

Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
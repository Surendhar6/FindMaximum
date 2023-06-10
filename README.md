# Find the maximum of a list of numbers

## Aim:
To write a program to find the maximum of a list of numbers.

## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
3.	
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value

## Program:

i)	# To find the maximum of marks using the list method sort.
```
''' 
Program to mark the maximum of marks using the list method sort
Developed by: Surendhar A
RegisterNumber: 212222110049
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```
''' 
Program to find the maximum marks using the list method max().
Developed by: Surendhar A
RegisterNumber: 212222110049
'''
def max_marks(marks):
    large=max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```
''' 
Program to the maximum marks without using builtin functions.
Developed by: Surendhar A
RegisterNumber: 212222110049
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
```
 
## Output:
i)	# To find the maximum of marks using the list method sort.
![image](https://github.com/Surendhar6/FindMaximum/assets/118352907/4c47a2a1-9926-4a28-bf74-7b03a322e9d6)

ii)	# To find the maximum marks using the list method max().
![image](https://github.com/Surendhar6/FindMaximum/assets/118352907/c31b8f1b-8fb8-4e7a-9971-17e59728cefe)

iii) # To find the maximum marks without using builtin functions.
![image](https://github.com/Surendhar6/FindMaximum/assets/118352907/86787143-8ba6-40f6-88ad-bf5cb3c2c52c)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.

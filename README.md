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
''' 
Program to mark the maximum of marks using the list method sort
Developed by: Yadhav.G.P
RegisterNumber: 23004895
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: Yadhav.G.P
RegisterNumber:23004895 
'''
def max_marks(marks):
    large=max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: Yadhav.G.P
RegisterNumber: 23004895
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i > max:
              max=i
    return max
```
## Output:
![1](https://github.com/iamyadhav/FindMaximum/assets/147139713/abfec6c8-dc2d-4c3d-81ff-850bb9110f91)
![2](https://github.com/iamyadhav/FindMaximum/assets/147139713/c632633f-08da-46a2-8611-dd996a555a51)
![3](https://github.com/iamyadhav/FindMaximum/assets/147139713/fc514a9b-76ae-4d74-828e-d8ef6eb23a2e)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.

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
Developed by: JANARTHANAN V K
RegisterNumber: 212222230051
'''
def max_marks(marks):
    marks.sort()
    max=marks[-1]
    return max
```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: JANARTHANAN V K
RegisterNumber: 212222230051 
'''
def max_marks(marks):
    l=max(marks)
    return l
```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: 
RegisterNumber: 
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i> max:
            max=i
    return max
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 
![findmax5](https://github.com/Janarthanan2/FindMaximum/assets/119393515/ece52539-268a-4070-90c0-8ab0bacf1759)
![Screenshot 2023-06-09 202812](https://github.com/Janarthanan2/FindMaximum/assets/119393515/c5e56c60-38ba-409f-b87b-dfea5e3dc0aa)

## Output:
i)	# To find the maximum of marks using the list method sort.
![Screenshot 2023-06-09 203026](https://github.com/Janarthanan2/FindMaximum/assets/119393515/a79084e6-3820-4368-beff-ff28499cf848)

ii)	# To find the maximum marks using the list method max().
![Screenshot 2023-06-09 203026](https://github.com/Janarthanan2/FindMaximum/assets/119393515/a79084e6-3820-4368-beff-ff28499cf848)

iii) # To find the maximum marks without using builtin functions.
![Screenshot 2023-06-09 203026](https://github.com/Janarthanan2/FindMaximum/assets/119393515/a79084e6-3820-4368-beff-ff28499cf848)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.

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
Developed by: Nandhini.E
RegisterNumber: 212222100030
'''
def max_marks(marks):
    marks.sort()
    return max(marks)


```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: E.NANDHINI
RegisterNumber: 212222100030
'''
def max_marks(marks):
    large=max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: E.NANDHINI
RegisterNumber: 212222100030
'''
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
![sort list](https://user-images.githubusercontent.com/121998147/236664675-09837c3f-f0a5-4ec5-8a53-6aaaae98e58d.png)

![max](https://user-images.githubusercontent.com/121998147/236664763-1627eaa5-7bcd-4899-96d1-575423f82663.png)

![builtin ](https://user-images.githubusercontent.com/121998147/236664818-10b188b8-06f2-481e-8ee3-5177941857e7.png)




## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.

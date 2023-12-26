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
Developed by: Harrish Venkat V
RegisterNumber: 23013973

def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```
''' 
Program to find the maximum marks using the list method max().
Developed by: Harrish Venkat V
RegisterNumber: 23013973

def max_marks(marks):
       marks.sort()
       large=marks[-1]
       return large


```

iii) # To find the maximum marks without using builtin functions.
```
Program to the maximum marks without using builtin functions.
Developed by: Harrish Venkat V
RegisterNumber: 23013973

def max_marks(list1):
            max= list1[0]
            for i in list1:
                if i >max:
                    max=i
            return max


```


## Output:
![image](https://github.com/HarrishVenkat/FindMaximum/assets/144979588/0c66752e-809b-4223-81c5-76de8f7e1292)
![image](https://github.com/HarrishVenkat/FindMaximum/assets/144979588/da4c6f73-7b8f-4c0b-a0f4-29703f3e28ce)
![image](https://github.com/HarrishVenkat/FindMaximum/assets/144979588/4dc90e5f-9c8b-4867-84a6-8b1626c1f2b3)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.

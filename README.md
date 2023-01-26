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
Developed by: mathan raj E 
RegisterNumber: 22008971
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
Developed by: Mathan raj
RegisterNumber: 22008971
'''
def max_marks(marks):
    return max(marks)

```

iii) # To find the maximum marks without using builtin functions.
```Python


''' 
Program to find the maximum marks using the list method max().
Developed by: Mathan raj E
RegisterNumber: 22008971
'''
def max_marks(marks):
    return max(marks)
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 


## Output:
1 output 
![max 1](https://user-images.githubusercontent.com/119560501/214871188-62924198-7e9b-4482-84e1-703b43b366dc.png)


2 output
![max2](https://user-images.githubusercontent.com/119560501/214871268-80c3ff64-544a-4bd0-8f20-1fb8f8ed62e7.png)

3 output

![max3](https://user-images.githubusercontent.com/119560501/214871401-c7173759-5e90-482d-ad84-d6ec48248095.png)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.

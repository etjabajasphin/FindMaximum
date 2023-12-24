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
~~~
''' 
Program to mark the maximum of marks using the list method sort
Developed by: 
RegisterNumber: 
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
~~~

ii)	# To find the maximum marks using the list method max().
~~~
''' 
Program to find the maximum marks using the list method max().
Developed by: 
RegisterNumber: 
'''
def max_marks(marks):
    marks.sort()
    res=marks[-1]
    return res
~~~

iii) # To find the maximum marks without using builtin functions.
~~~
''' 
Program to the maximum marks without using builtin functions.
Developed by: 
RegisterNumber: 
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
~~~

## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![image](https://github.com/etjabajasphin/FindMaximum/assets/139336455/b9681265-5104-4e41-9877-6f5e65561c71)
![image](https://github.com/etjabajasphin/FindMaximum/assets/139336455/af542f19-cdb5-414f-9d62-207bcd8602d4)
![image](https://github.com/etjabajasphin/FindMaximum/assets/139336455/c3a6456a-8b94-40da-b3a9-797f54e86d4c)








## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.

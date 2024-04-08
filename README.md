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

Developed By: SANDHIYA.R

Register No:212223240146 

i)	# To find the maximum of marks using the list method sort.
```Python
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```
Developed By: SANDHIYA.R

Register No:212223240146 

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(marks):
    large=marks[len(marks)-1]
    marks.sort(reverse=True)
    large=marks[0]
    return large
```
Developed By: SANDHIYA.R

Register No:212223240146 

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(marks):
    maxmark=0
    for i in marks:
        if i>maxmark:
            maxmark=i
    return maxmark

```
## Output:
![Screenshot (154)](https://github.com/SandhiyaRajagopal/FindMaximum/assets/144870852/7f52e8f5-0f97-4ed8-ba7c-4146992c72ef)

![Screenshot (155)](https://github.com/SandhiyaRajagopal/FindMaximum/assets/144870852/436fca43-e7f7-4065-b460-ffb7c4d1e831)

![Screenshot (156)](https://github.com/SandhiyaRajagopal/FindMaximum/assets/144870852/f0e56e59-ac5f-4284-802a-d8a953ef8ad2)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.

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

#program developed by :javan rufus j
#roll num:212224230104
def max_marks(a):
    a.sort()
    return a[9]

```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(a):
    return max(a)


```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(a):
    max =a[0]
    for i in a:
        if(i>max):
            max=i
    return max
        
    


```



## Output:
![p6 1](https://github.com/user-attachments/assets/12236f2a-8aac-42e4-9f1e-e781e5597f47)
![p 6 2](https://github.com/user-attachments/assets/6c673852-98b8-47bd-91d3-599c4747d0cb)
![p6 3](https://github.com/user-attachments/assets/0a807e9b-c693-41ed-b03a-aef8232dd22b)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.

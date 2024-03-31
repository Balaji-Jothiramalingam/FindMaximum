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


def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```



def max_marks(marks):
    large=marks[len(marks)-1]
    marks.sort(reverse=True)
    large=marks[0]
    return large

```

iii) # To find the maximum marks without using builtin functions.
```

def max_marks(marks):
    maxmark=0
    for i in marks:
        if i>maxmark:
            maxmark=i
    return maxmark



```



## Output:

i] To find the maximum of marks using the list method sort.

![318194454-d2d4244e-d3bb-4a47-9d22-5d50083fe200](https://github.com/Balaji-Jothiramalingam/FindMaximum/assets/114234865/23f11d48-6142-4be1-865c-a4d66dd89b8a)

ii] To find the maximum marks using the list method max().

![318194462-1e1e43cc-12d7-43a0-8bf4-236cb874ebd4](https://github.com/Balaji-Jothiramalingam/FindMaximum/assets/114234865/ebbf2553-3bb7-4d81-8472-ba79fc553bda)

iii] To find the maximum marks without using builtin functions.

![318194474-e2cca978-a39e-40d5-9d4b-152fa9167661](https://github.com/Balaji-Jothiramalingam/FindMaximum/assets/114234865/22c9c16c-0c4c-4306-a671-133e64efb78c)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.

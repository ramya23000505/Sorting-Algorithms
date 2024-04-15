# Selection sort and Insertion sort
## Aim:
To write a program to perform selection sort and insertion sort using python programming.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Selection Sort Algorithm:
1.	Set the first unsorted element as the minimum
2.	For each of the unsorted elements, check if the element < current minimum.
3.	If yes, set the element as the new minimum.
4.	Swap minimum with first unsorted position.
5.	Repeat the steps 2 and 3 for all the elements in the array.
## Insertion Sort Algorithm:
1.	Set the first element as sorted element j.
2.	For each unsorted element X, check if current sorted element j >X.
3.	If yes, move sorted element to the right by 1.
4.	Break the loop and insert X.
5.	Repeat the steps 2 to 4 for sorting all the elements in the array.
## Program:
i)	#Selection Sort
```
'''
program to sort the elements in the list using the Selection Sort algorithm
Developed by Ramya R
Register No: 212223230169
'''
num=eval(input())
for i in range(len(num)):
    low=i
    for j in range(i+1,len(num)):
        if num[j]<num[low]:
            low=j
    num[i],num[low]=num[low],num[i]
print(num)
```
ii)	#Insertion Sort
```
'''
program to sort the elements in the list using the Selection Sort algorithm
Developed by Ramya R
Register No: 212223230169
'''
num=eval(input())
for i in range(1,len(num)):
    insert=num[i]
    j=i-1
    while j>=0 and num[j]>=insert:
        num[j+1]=num[j]
        j=j-1
    num[j+1]=insert
print(num)
```

## Output:
# Selection Sort
![Screenshot 2024-04-15 135636](https://github.com/ramya23000505/Sorting-Algorithms/assets/149370791/bc7e427e-c611-4104-8d81-d4f19b518edc)
![Screenshot 2024-04-15 135641](https://github.com/ramya23000505/Sorting-Algorithms/assets/149370791/2c3dd661-5801-4bbd-9bfe-e6dfbf78a8d2)
# Insertion Sort
![Screenshot 2024-04-15 135806](https://github.com/ramya23000505/Sorting-Algorithms/assets/149370791/f833c572-e148-4de1-8817-3d2198a0359e)
![Screenshot 2024-04-15 135812](https://github.com/ramya23000505/Sorting-Algorithms/assets/149370791/74d6d0b7-39a6-4628-9319-f57b3e2b420e)

## Result:
Thus the program is written to perform selection sort and insertion sort using python programming.

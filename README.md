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
program to sort the elements using selection sort
Developed by: EASWAR R
Register number: 212223230053
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
program to sort the elements using Insertion sort
Developed by: EASWAR R
Register number: 212223230053
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
i)	#Selection Sort

![image](https://github.com/EaswarR2005/Sorting-Algorithms/assets/146931525/22f78a6f-9762-4333-bdda-7a0413aa65ac)
![image](https://github.com/EaswarR2005/Sorting-Algorithms/assets/146931525/dc11950c-643c-49db-b0a0-450a7223b8a6)

ii)	#Insertion Sort

![image](https://github.com/EaswarR2005/Sorting-Algorithms/assets/146931525/4c3e8e74-738e-4195-b2fb-c3621551a846)
![image](https://github.com/EaswarR2005/Sorting-Algorithms/assets/146931525/5df95ba5-1276-4ce7-9c37-c6e19cd859b9)

## Result:
Thus the program is written to perform selection sort and insertion sort using python programming.

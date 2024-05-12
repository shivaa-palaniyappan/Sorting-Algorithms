# EXP-8 Selection sort and Insertion sort
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

DEVELOPED BY:SHIVAA PALANIYAPPAN V

REGISTER NUMBER:212223110050

i)	#Selection Sort
```
Unsorted = eval(input())
def selSort(Unsorted):
    n = len(Unsorted)
    for i in range(n-1):
        min_pos = i
        for j in range(i,n):
            if  Unsorted[j]<Unsorted[min_pos]:
                Unsorted[j],Unsorted[min_pos] = Unsorted[min_pos],Unsorted[j]
    return Unsorted
print(selSort(Unsorted))   




```
ii)	#Insertion Sort
```

Unsorted = eval(input())
def selSort(Unsorted):
    n = len(Unsorted)
    for i in range(n-1):
        min_pos = i
        for j in range(i,n):
            if  Unsorted[j]<Unsorted[min_pos]:
                Unsorted[j],Unsorted[min_pos] = Unsorted[min_pos],Unsorted[j]
    return Unsorted
print(selSort(Unsorted)) 





```

## Output:
## SELECTION SORT
![image](https://github.com/shivaa-palaniyappan/Sorting-Algorithms/assets/146915611/5325c902-6913-4134-9819-06c314699428)
## INSERTION SORT
![image](https://github.com/shivaa-palaniyappan/Sorting-Algorithms/assets/146915611/652a963e-b710-41b7-af4f-84f822811555)


## Result:
Thus the program is written to perform selection sort and insertion sort using python programming.

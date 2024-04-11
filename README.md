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
Developed by:SANJAI L
Register No: 212223230184
Unsorted=eval(input())
def selsort(Unsorted):
  n = len(Unsorted)
  for i in range(n-1):
    min_pos = i
    for j in range(i,n):
      if Unsorted[j]<Unsorted[min_pos]:
        Unsorted[j],Unsorted[min_pos] = Unsorted[min_pos],Unsorted[j]
  return Unsorted
print(selsort(Unsorted))

```
ii)	#Insertion Sort
```
Developed by:SANJAI L
Register No: 212223230184
def Insertionsort(arr):
  for i in range(1,len(arr)):
    j = i
    while arr[j]<arr[j-1] and j>0:
      arr[j],arr[j-1] = arr[j-1], arr[j]
      j-=1
  return arr
arr = eval(input())
print(Insertionsort(arr))

```

## Output:
![image](https://github.com/SanjaiOfficial/Sorting-Algorithms/assets/151763180/c5fffe24-3193-494a-8f09-8b5fef3782e8)

![Screenshot 2024-04-06 213428](https://github.com/SanjaiOfficial/Sorting-Algorithms/assets/151763180/87c2e686-b54b-4d7b-9c79-d717b2babca7)
![image](https://github.com/SanjaiOfficial/Sorting-Algorithms/assets/151763180/4d3e532e-50f4-4e07-b9eb-5c3e578d770d)

![Screenshot 2024-04-06 213448](https://github.com/SanjaiOfficial/Sorting-Algorithms/assets/151763180/a8257e55-8860-45eb-b063-6a46779679f8)




## Result:
Thus the program is written to perform selection sort and insertion sort using python programming.

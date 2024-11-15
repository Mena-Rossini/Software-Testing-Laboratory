### Ex.No: 5 Write a program in Python language to search a given element is present in the list using Binary search.
### DATE:13-9-2024
### REGISTER NUMBER : 212222040099
### AIM: 
Write a program in Python language to search a given element is present in the list using Binary search. Introspect the causes for its failure and write down the possible reasons for its failure.

### Algorithm:

1.  Initialize low to 0 and high to the last index of the list.
2.  Repeat while low is less than or equal to high:
3.  Calculate mid as low + (high - low) // 2.
4.  Compare the target with the middle element.
5.  If the target is found, return the index.
6.  If the target is smaller, adjust high to mid - 1.
7.  If the target is larger, adjust low to mid + 1.
8.  If low exceeds high, return -1 (target not found).

### Program:
```
def binary_search(arr, x):  
    low = 0 
    high = len(arr) - 1 
    mid = 0 
    while low <= high: 
        mid = (high + low) // 2  
        if arr[mid] < x: 
            low = mid + 1 
        elif arr[mid] > x: 
            high = mid - 1 
        else: 
            return mid
    return -1 
 
arr = [ 2, 3, 4, 10,40 ] 
x = input("Enter the element to be searched: ");  
try: 
    x = int(x) 
    result = binary_search(arr, x)  
    if result != -1: 
          print("Element is present at index",str(result)) 
    else: 
          print("Element is not present in array") 
except: 
    print("Enter a valid input!")
```
### Output:

![exp5](https://github.com/user-attachments/assets/733a3571-d927-4f0c-98c2-49501a740c75)


### Result:
Thus, the python program to check the number is Armstrong number or not implemented and the output is verified successfully.


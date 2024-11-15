# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE: 16-08-2024                                                                           
### REGISTER NUMBER : 212222040099

### AIM:  
To write python programs for do…while, while, for, switch and if…else and test with possible test Cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.

### Program:
### do...while:
```
def display(): 
    start=input("Enter a positive value for START: ") 
    end=input("Enter a positive value for END: ") 
    if start.isnumeric() and end.isnumeric(): 
        while True: 
            start=int(start) 
            end=int(end) 
            print(start,end=" ") 
            if start<end: 
                start+=1 
            else: 
                break 
    else: 
        print("Enter a valid positive number.") 
display() 
```
### while...do:
```
start=input("Enter a positive value for START: ") 
end=input("Enter a positive value for END: ") 
if start.isnumeric() and end.isnumeric(): 
    start=int(start) 
    end=int(end) 
    while start<end: 
        print(start) 
        start+=1 
else: 
    print("Enter a valid positive number.")
```
### switch:
```
def switch(): 
    switcher={ 0:"even", 1:"odd" } 
    n=input('Enter a value for N: ') 
    try: 
        n=int(n) 
        print(switcher[n%2]) 
    except ValueError: 
        print("Enter a valid number.") 

switch() 
```
### if..else:
```
def compare(): 
    a=input("Enter a value for A: ") 
    b=input("Enter a value for B: ") 
    try: 
        a=int(a) 
        b=int(b) 
        if a>b: 
            print("A is greater than B") 
        elif a<b: 
            print("B is greater than A") 
        else: 
            print("A is equal to B") 
    except ValueError: 
        print("Enter a valid number.")

compare()
```
### for:
```
def iterate(): 
    string=input("Enter a string: ") 
    for i in string: 
        print(ord(i),end=" ") 
iterate()
```

### Output:
### do...while:

![exp1a_!](https://github.com/user-attachments/assets/2827f6f1-3670-463d-9cec-ce4260766f3b)

![exp 1a_2](https://github.com/user-attachments/assets/330691bd-1338-48d8-9adf-56d0501a89bf)


### while...do:

![exp 1b](https://github.com/user-attachments/assets/e250180b-5af8-47fe-a050-1a738c0503fb)


### switch:

![exp 1c](https://github.com/user-attachments/assets/df6b1af4-4d46-432a-80c2-7f6f1c4ac78f)


### if..else:

![exp 1d](https://github.com/user-attachments/assets/5c0d22c0-3a1f-435b-90b3-0c0be05aafd3)


### for:

![exp1e (2)](https://github.com/user-attachments/assets/3ff67dc2-1417-4787-a481-18bd512f02b5)

### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.



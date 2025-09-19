# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### NAME: NITHISH R                                                                         
### REGISTER NUMBER : 212222040107

### AIM:  
To write python programs for do…while, while, for, switch and if…else and test with possible test 
Cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.
### Program:

## Do while
```
def display():
    start=input("Enter a positive value for START: ")
    end=input("Enter a positive value for END: ")
    if start.isnumeric() and end.isnumeric():
        while True:
            start=int(start)
            end=int(end)
            print(start,end=' ')
            if start<end:
                start+=1
            else:
                break
    else:
        print("Enter a valid positive number.")
display()
```

## while do

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

## Switch

```
def switch():
    switcher={0:"even",1:"odd"}
    n=input('Enter a value for N: ')
    try:
        n=int(n)
        print(switcher[n%2])
    except ValueError:
        print("Enter a valid number.")
switch()

```

## If else

```
def compare():
    a=input("Enter a value for A: ")
    b=input("Enter a value for B: ")
    try:
        a=int(a)
        b=int(b)
        if a>b:
            print("A is greater than")
        elif a<b:
            print("B is greater than")
        else:
            print("A is equal to B")
    except ValueError:
        print("Enter a valid number.")

compare()
```

## for

```
def iterate():
    string=input("Enter a string: ") 
    for i in string:
        print(ord(i),end=" ")
iterate()
```

### Output:

## Do while
<img width="1912" height="607" alt="do_while" src="https://github.com/user-attachments/assets/c9f1c5f6-9d84-4984-aec9-7d0b936da999" />


## While do
<img width="1912" height="565" alt="while_do" src="https://github.com/user-attachments/assets/00b9bcda-404f-42b3-a4e3-3a5bca2a07a9" />


## Switch
<img width="1906" height="486" alt="switch" src="https://github.com/user-attachments/assets/502265a8-b325-4e20-b1fe-ef0779bba1f7" />


## If else
<img width="1905" height="557" alt="if_else" src="https://github.com/user-attachments/assets/03395d1b-ac9c-4898-9ced-439821b2fc0b" />


## for
<img width="1910" height="356" alt="for" src="https://github.com/user-attachments/assets/bb71e26c-6d2c-4a1f-937b-8b3fc41a3442" />



### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.

# GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### Step 1:
Define a function.
### Step 2:
Get the two numbers from the user.
### Step 3: 
Compare the two values, to find the smaller number.
### Step 4:
Use for() and if() loop to find the GCD of the two numbers.

## Program:
```
#GCD of two numbers
#Developed by: Prajin S
#Register number: 23012918
def gcd():
    n1,n2=int(input()),int(input())
    if n1>n2:
        small=n2
    else:
        small=n1
    for i in range(1,small+1):
        if(n1%i==0 and n2%i==0):
            hcf=i
    print('GCD of two numbers is:',hcf)
```

## Output:
![Gcd](https://github.com/Prajin19/GCD-of-two-numbers/assets/144979377/7f41e63f-4227-4913-b1e9-ad39b7754216)



## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.

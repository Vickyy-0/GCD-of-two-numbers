# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner
``````
## Algorithm
1. Define a function.
2. Get the two numbers from the user.
3. Compare the two values, to find the smaller number.
4. Use for() and if() loop to find the GCD of the two numbers.
5.use range function for determining the start and stop value.
6.use append function to append the numbers to the end
7.print the reverse index of the string
``````

## Program:
```
/*
Program to find the gcd of two number using function.
Developed by: vignesh.v
RegisterNumber: 23002301
*/

list=[]
n1=int(input())
n2=int(input())
def gcd():
    print()
for i in range(1,n1+1):
 if n1%i==0 and n2%i==0:
    list.append(i)
print("GCD of two numbers is:",list[-1])

``````

## Output:
<img width="565" alt="image" src="https://github.com/Vigneshv-23/GCD-of-two-numbers/assets/110780412/9fa8bc18-e740-46b8-ba13-c76bd9d10f60">



## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming

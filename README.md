
## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Get the two numbers from the user.
3. Compare the two values, to find the smaller number.
4. Use for() and if() loop to find the GCD of the two numbers.

## Program:
```
Program to find the gcd of two number using function.
Developed by:KATHIRESAN K 
RegisterNumber:  212223110021

```
```

def gcd():
    num1,num2=int(input()),int(input())
    if num1<num2:
        smaller=num1
    else:
        smaller=num2
    for i in range(1,smaller+1):
        if num1%i==0 and num2%i==0:
            gcd1=i
    print("GCD of two numbers is:",gcd1)
     

```

## Output:
![Screenshot 2024-04-14 165717](https://github.com/Kathiresan-23013376/GCD-of-two-numbers/assets/150008375/3594b4c0-cf49-456e-8e99-6eac5a5b3159)

![image](https://github.com/Kathiresan-23013376/GCD-of-two-numbers/assets/150008375/e43a907b-be69-4852-9557-c75096978db3)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.

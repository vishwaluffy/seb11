
##Aim
To write a program to find maximum between three float numbers using conditional Expression(Ternary)

##Alogrithm
1. Start.
2. Input three float numbers: `a, b, c`.
3. Compute max using ternary: max_val = a if a > b and a > c else (b if b > c else c).
4. Output max_val as the maximum

##Program

```
a=eval(input())
b=eval(input())
c=eval(input())


if(a>b):
    
    if(b>c):
       print(f"The maximum of {a}, {b}, {c} is {a}")
    else:
          print(f"The maximum of {a}, {b}, {c} is {c}")
else:
    if(a>c):
          print(f"The maximum of {a}, {b}, {c} is {b}")
    else:
          print(f"The maximum of {a}, {b}, {c} is {b}")
```

##output
![Image](https://github.com/user-attachments/assets/215eb36f-38f3-4f75-9945-3dcb7b2eceab)

##result
```
The Expected output is achieved.
```

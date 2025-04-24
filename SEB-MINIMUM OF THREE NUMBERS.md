# Experiment No: 5 – Smallest of Three Numbers

## AIM  
To write a python program to find the smallest among three Integer Numbers

## ALGORITHM  

1. Start the program.
2. Accept three numbers from the user and store them in variables a, b, and c.
3. Use an if statement to check if a is less than both b and c. If true, assign a to s.
4. Else if b is less than both a and c, assign b to s.
5. Otherwise, assign c to s.
6. Print the smallest value along with the inputs.
7. End the program.


## PROGRAM
```python
# Reg.No-212223050032
# Name-Nidhish B

a=int(input())
b=int(input())
c=int(input())
if a<b and a<c:
    s=a
elif b<a and b<c:
    s=b
else:
    s=c
print(f"The Smallest  of the three a= {a} b= {b} c= {c} is {s}")
```

## OUTPUT

![image](https://github.com/user-attachments/assets/85900c5b-a38d-47fc-9bea-dedcf17ee4b1)


## RESULT

Thus, the python program to find the smallest among three Integer Numbers was successfully executed.

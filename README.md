# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Get the two values from the user
### Step 2: 
Get the value from the user for the number of rotation
### Step 3: 
Using the slicing concept rotate the list
### Step 4: 
Print the circulated string
### Step 5: 
End the program

## Program:
```
#Program to circulate N values.
#Developed by: SRI KARTHICKEYAN GANAPATHY
#RegisterNumber:22008592
def circulate():
    a=eval(input())
    b=int(input())
    c=a[b:]+a[:b]
    print("After circulating the values are:",c)
```

## Output:
![OUTPUT](op2.png)

## Result:
Thus the program to circulate the values of n variables is executed.

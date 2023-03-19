# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Get the two lists from the user
### Step 2: 
Get the value from the user for the number of rotation
### Step 3: 
Using the slicing concept rotate the list
### Step 4: 
Print the values 
### Step 5: 
End the program
## Program:
```
#Program to circulate N values.
#Developed by: N.Kishore
#RegisterNumber: 212222240049
def circulate():
    list1=eval(input())
    n=int(input())
    result=list1[n:]+list1[:n]
    print("After circulating the values are:",result)
```
## Output:
![Circulate-the-values-of-N-variables](pyex2pic.png)

## Result:
Thus the program to circulate the values of N variables is successfully executed.

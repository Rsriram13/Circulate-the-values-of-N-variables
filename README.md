# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:
Start the program 
### Step 2: 
Get the input from user using eval(input)
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
Using concatination operation dispaly in the entire rorated list
### Step 6:
Stop the program 
## Program:
```
#Program to circulate N values.
#Developed by: sriram R
#RegisterNumber:23004952
def circulate():
    list1=eval(input())
    n=int(input())
    result=list1[n:]+list1[:n]
    print("After circulating the values are:",result)
```
## Output:
![output](https://github.com/Rsriram13/Circulate-the-values-of-N-variables/assets/145742823/37fed4d3-6d78-4d81-8439-f31f7dbc613d)

## Result:
Thus Circulate the values of N variables are successfully executed

# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
define a function
### Step 2: 
get a user value from the user
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
print the number
### Step 6: 
end the program
## Program:
```python
#Program to circulate N values.
#Developed by: sharangini
#RegisterNumber: 22003363
def circulate():
    a=eval(input())
    n=int(input())
    a=a[n:]+a[:n]
    print('After circulating the values are:',a)
```

## Output:
![output](/cv.png)

## Result:
This is the program to circulate the values of N varibles using function concept is written and verified using python programming
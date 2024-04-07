## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Get the values from the user
### Step 2: 
Assign the value of variable to a temporary variable
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Print both the values it would be interchanged
### Step 6: 
End the program
## Program:
```
# Program Name : Circulate-the-values-of-N-variables
# Name : SANJAYKUMAR N B
# Register Number : 212223230189
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print('After circulating the values are:',l)
```
## Output:
![image](https://github.com/sanjaykumar-nb/Circulate-the-values-of-N-variables/assets/154039979/f2e431c8-ca2a-4e65-a859-7b16e4dfaa0f)


## Result:
The output for circulate the values of n variables is successfull.

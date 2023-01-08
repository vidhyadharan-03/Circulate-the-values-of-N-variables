# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:
creating a function 
### Step 2: 
Get the list which need to be circulated.
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Printing the circulated value
### Step 6: 
## Program:
~~~py
def circulate():
    a=eval(input())
    b=int(input())
    c=a[b:]+a[:b]
    print("After circulating the values are:",c)
~~~

## Output:
![input and expected ](/circulating%20n%20variables.png)
![ciruclating n variables](/circulate.png)

## Result:
Thus using python program the circulation of the value of N variable has been executed successfully.

# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Define the circulate function
### Step 2: 
Accept the list of values from the user
### Step 3: 
Accept the number of positions to circulate (n) from the user
### Step 4: 
Circulate the values by slicing
### Step 5: 
Print the result
### Step 6: 
End the Program
## Program:
 ```   
#Program to circulate N values.
#Developed by: Shree lekha.S
#RegisterNumber:23014046
def circulate():
    l=eval(input())
    n=int(input())
    c=l[n:]+l[:n]
    print("After circulating the values are:",c)

```  


## Output:
![output](/circulateoutput.png)

## Result:
Thus the circulate the values of N variables are successfully executed
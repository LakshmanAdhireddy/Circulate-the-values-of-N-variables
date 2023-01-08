# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
Step 1:
import the numpy module to use the built- in functions for caculation.

Step 2:
Prepare the lists from each circulate the values and assign in np.array().

Step 3:
Get the value from the user for the number of rotation.

Step 4:
Using the slicing concept rotate the list.

Step 5:
End the program.

## Program:
~~~
#Program to circulate N values.
#Developed by: Lakshman reddy
#RegisterNumber: 22004423
def circulate(): 
    X = [10,20,30,40,50,60]
    n=int(input())
    X = X[n:]+X[:n]
    print("After circulating the values are:",X)
 l=eval(input())
 n=int(input())
    
 ~~~

## Output:
![Screenshot (11)](https://user-images.githubusercontent.com/118707265/211195697-5b6941e5-2d6b-4520-9438-8ec90398734c.png)


## Result:
Thus circulating the n variables using python are successfully executed.

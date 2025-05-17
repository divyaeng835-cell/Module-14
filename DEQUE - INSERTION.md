# Exp.No:39  
## DEQUE - INSERTION

### AIM  
To write a Python program to insert elements at REAR END of deque using a collection built-in function.

### ALGORITHM  

1. Import the `deque` class from the `collections` module.  
2. Initialize an empty deque.  
3. Start an infinite loop using `while True`.  
4. In each iteration, take input from the user.  
5. If the input is an empty string, break the loop.  
6. If the input is not empty, convert it to an integer and append it to the deque.  
7. After the loop ends, append the values `14` and `15` to the deque.  
8. Print the message `"The deque after appending at right is :"`.  
9. Print the contents of the deque.  

### PROGRAM  

```
from collections import deque
n=int(input())
n1=int(input())
n2=int(input())
de=deque([n,n1,n2])
de.append(14)
de.append(15)
print("The deque after appending at right is :")
print(de)

```

### OUTPUT
![Screenshot 2025-05-17 133810](https://github.com/user-attachments/assets/c26210b9-bb8f-4a2c-9a61-bf64d67d0a4b)
### RESULT
Thus the python program to insert elements at REAR END of deque using a collection built-in function has been implemented and executed

# Exp.No:38  
## Deque - DELETION

---

### AIM  
To write a Python program to delete elements at FRONT END of deque using a collection built-in function.

---

### ALGORITHM  

1. Import the `deque` class from the `collections` module.  
2. Create an empty deque.  
3. Define how many elements to input (e.g., 3 inputs as in the example).  
4. Loop through the range of input size:  
   - Read an integer from the user.  
   - Append the integer to the deque.  
5. Remove the front element of the deque using `popleft()`.  
6. Print the final deque after deletion.  

---

### PROGRAM  

```
import collections
n1=input()
n2=input()
n3=input()

col=collections.deque([n1,n2,n3])

col.popleft()

print("The deque after deletion is :")
print(col)
```

### OUTPUT
<img width="830" height="241" alt="443754683-b66575d8-4179-48cf-977c-f42cb0d14234" src="https://github.com/user-attachments/assets/97ac81b3-e1d6-436c-a20d-17da7d7a66a2" />


### RESULT
Thus , the given python program is implemented and executed sucessfully.

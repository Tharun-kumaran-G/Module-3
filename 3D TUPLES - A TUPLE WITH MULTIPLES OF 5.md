# Exp.No:3d  
## TUPLES - A TUPLE WITH MULTIPLES OF 5

---

### AIM  
To write a Python program to create a tuple containing all multiples of 5 up to a given number **N**.

---

### ALGORITHM

1. Begin the program.  
2. Accept an integer `N` from the user.  
3. Use a generator expression inside the `tuple()` function to create a tuple `multiples_of_5` with values starting from `5` up to `N - 1`, stepping by `5`.  
4. Return the tuple `multiples_of_5`.  
5. Print the resulting tuple.  
6. Terminate the program.

---

### PROGRAM

```
#Reg_no: 212223060288
#Name: Tharun Kumaran G

def create_multiples_of_5_tuple():
    N = int(input("Enter a number: "))
    multiples_of_5 = tuple(num for num in range(5, N + 1, 5))
    print("Multiples of 5 up to", N, ":", multiples_of_5)

create_multiples_of_5_tuple()

```

### OUTPUT

![image](https://github.com/user-attachments/assets/69217903-b2ec-44c0-b744-ef6d8647653e)

### RESULT

Thus, the python program to create a tuple containing all multiples of 5 up to a given number **N** has been executed and verified successfully.

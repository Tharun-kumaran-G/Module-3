# Exp.No:3c
## LIST - EVEN NUMBERS LIST

---

### AIM  
To write a Python function that accepts a number **N** and creates a list containing all even numbers up to **N**.

---

### ALGORITHM

1. Begin the program.  
2. Accept an integer `a` from the user.  
3. Create an empty list `l`.  
4. Use a `for` loop to iterate through numbers from `1` to `a - 1`:  
   - For each number `i`, check if it is even using `i % 2 == 0`.  
   - If it is even, append `i` to the list `l`.  
5. Print the final list `l` containing all the even numbers.  
6. Terminate the program.

---

### PROGRAM

```
#Reg_no: 212223060288
#Name: Tharun Kumaran G

def get_even_numbers_up_to_n():
    N = int(input())
    even_numbers = [num for num in range(0, N + 1) if num % 2 == 0]
    print(even_number)

get_even_numbers_up_to_n()

```

### OUTPUT

![image](https://github.com/user-attachments/assets/ad504145-152e-41a3-9ca8-4c2cc493eae8)

### RESULT

Thus, the Python function that accepts a number **N** and creates a list containing all even numbers up to **N** has been executed and verified successfully.

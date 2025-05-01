# Exp.No:3e
## SEB - STRING SLICING

---

### AIM  
To write a Python function that accepts a string and forms a new string by reversing the characters from the **4th position to the 10th position** with **alternate characters**, and then prints the new string.

---

### ALGORITHM

1. Begin the program.  
2. Accept a string as input.  
3. Take a slice of the input string from index **2** to **10** (Python uses 0-based indexing, so index 2 refers to the 3rd character, i.e., the 4th character in natural terms).  
4. Reverse the sliced substring.  
5. Extract every second character from the reversed substring using slicing (`[::2]`).  
6. Print the final processed string.  
7. Terminate the program.

---

### PROGRAM

```
#Reg_no: 212223060288
#Name: Tharun Kumaran G

def reverse_substring_with_alternate_chars():
    input_str = input("Enter a string: ")
    if len(input_str) < 11:
        print("The string must be at least 11 characters long.")
        return
    sub_str = input_str[3:10:2]
    reversed_sub_str = sub_str[::-1]
    new_string = input_str[:3] + reversed_sub_str + input_str[10:]
    print("New string:", new_string)

reverse_substring_with_alternate_chars()

```

### OUTPUT

![image](https://github.com/user-attachments/assets/cdaf27f0-2c07-4d18-8d18-dc5611656a47)

### RESULT

Thus, the python function that accepts a string and forms a new string by reversing the characters from the **4th position to the 10th position** with **alternate characters**, and then prints the new string has been executed and verified successfully.

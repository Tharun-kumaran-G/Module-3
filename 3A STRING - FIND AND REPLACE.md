# Exp.No:3a
## STRING - FIND AND REPLACE

---

### AIM  
To write a Python function to accept a string, identify a word to be replaced, and replace it with a new word provided by the user.

---

### ALGORITHM

1. Begin the program.  
2. Input the original string `str1` and the word to be replaced `replace_str`.  
3. Ask the user to input the new replacement word `str2`.  
4. Use the `replace()` method in Python to replace all occurrences of `replace_str` in `str1` with `str2`.  
5. Store the modified string in `str3`.  
6. Display the original string (`str1`) and the modified string (`str3`).  
7. Terminate the program.

---

### PROGRAM

```
#Reg_no: 212223060288
#Name: Tharun Kumaran G

def replace_word_in_string():
    original_string = input("Enter the original string: ")
    old_word = input("Enter the word to be replaced: ")
    new_word = input("Enter the new word: ")
    updated_string = original_string.replace(old_word, new_word)
    
    print("Updated string:", updated_string)

replace_word_in_string()


```

### OUTPUT

![image](https://github.com/user-attachments/assets/b84fd22e-f37d-4fe4-bd7d-379d79aebf95)

### RESULT

The python function to accept a string, identify a word to be replaced, and replace it with a new word provided by the user has been executed and verified successfully.

# Exp.No:3b  
## REGEX - PATTERN MATCHING USING REGEX

---

### AIM  
To write a Python program that matches a string containing an `'a'` followed by **two to three `'b'` characters** using regular expressions.

---

### ALGORITHM

1. Begin the program.  
2. Accept a string `str1` from the user.  
3. Define the regular expression pattern as `r"[a]+b{2,3}"`.  
4. Use the `re.match()` function to check if the string `str1` matches the pattern.  
5. If a match is found, print `"Found a match!"`.  
6. If no match is found, print `"Not matched!"`.  
7. Terminate the program.

---

### PROGRAM

```
#Reg_no: 212223060288
#Name: Tharun Kumaran G

import re
def match_a_bb_or_bbb():
    test_string = input("Enter a string: ")
    pattern = r"ab{2,3}"
    match = re.search(pattern, test_string)

    if match:
        print("Match found:", match.group())
    else:
        print("No match found.")

match_a_bb_or_bbb()

```
### OUTPUT

![image](https://github.com/user-attachments/assets/a7df8310-9e12-462f-956f-afd2aa2e13db)

### RESULT

Thus,the python program that matches a string containing an `'a'` followed by **two to three `'b'` characters** using regular expressions has been executed and verified successfully.


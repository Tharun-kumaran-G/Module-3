# Exp.No:3a
## STRING - COUNT THE VOWELS OF A GIVEN STRING.
---

### AIM  
To write a Python function to count the vowels of a given string.

---

### ALGORITHM

1. Take a string input from the user.
2. Initialize a dictionary to count vowels (`a`, `e`, `i`, `o`, `u`).
3. Set a flag variable to `False`.
4. Loop through each character in the string.
5. If the character is a vowel, increment its count and set the flag to `True`.
6. After the loop, if the flag is still `False`, print "There are no vowels".
7. Otherwise, print each vowel and its count if the count is not zero.


---

### PROGRAM

```
#Reg_no: 212223060288
#Name: Tharun Kumaran G

str=input()

vow={'a':0,'e':0,'i':0,'o':0,'u':0}

flag=False

for i in str:

if i in vow:
    vow[i]+=1
    flag=True
if flag==False:

print(f"There are no vowels in {str}")
else:

for i in vow:
    if vow[i]:
        print(f"Vowel:  {i} {vow[i]}")


```

### OUTPUT

![image](https://github.com/user-attachments/assets/a64232fb-b5b6-43d0-a660-1c2eaac4d5c5)

### RESULT

The python function to count the vowels of a string has been executed and verified successfully.

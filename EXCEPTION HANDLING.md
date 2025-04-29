# Exp.No:17  
## EXCEPTION HANDLING

---

### AIM  
To create a Python program that prompts the user for a list of grades separated by commas, splits the string into individual grades, and uses exception handling to inform the user if the values they entered cannot be converted to integers.

---

### ALGORITHM

1. Begin the program.  
2. Read a string `input_str` from the user using `input()`.  
3. Split the input string using commas (`,`) to create a list of grades.  
4. Use a `try` block to attempt converting each item in the grades list to an integer and store the result in `l1`.  
5. If the conversion is successful, print the list `l1` containing the integer values.  
6. If an error occurs during conversion (for example, if the input is not a valid number), catch the exception and print an error message: `"The grades you entered were in an invalid format."` along with the original grades list.  
7. Terminate the program.

---

### PROGRAM

```
Reg.No : 212223020021
Name : Ranjith P
Add Your Code Here

def Guess(a):
    secret=10
    while True:
        try:
            if guess==secret:
                print("Congratulations! You guessed it correctly.")
                break
            elif guess>secret:
                print("This value is too large, try again!")
                
                break
            else:
                print("This value is too small, try again!")
                break
        except value:
            print("rg")
guess=int(input()) 
Guess(guess)
```

### OUTPUT
![image](https://github.com/user-attachments/assets/5e539996-ae47-4f2b-8569-104d9f1a1c23)

### RESULT
The program successfully raises a user-defined exception if the user guesses incorrectly and prints an error message.

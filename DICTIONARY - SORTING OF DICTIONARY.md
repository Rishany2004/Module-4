# Exp.No:16  
## DICTIONARY - SORTING OF DICTIONARY

### AIM  
To write a Python program that sorts the keys and values in alphabetical order based on dictionary values.

### ALGORITHM
1. Begin the program.
2. Define a dictionary with keys and corresponding values.
3. Sort the dictionary by values in alphabetical order using the sorted() function.
4. Display the sorted dictionary.
5. End the program.

### PROGRAM

```
dict = {2: 56, 1: 2, 5: 12, 3: 323, 4: 24, 6: 18}
sort_dict = sorted(dict.items(), key=lambda item: item[1])
print('Keys and Values sorted in alphabetical order by the value')
print(sort_dict)
```
### OUTPUT

![image](https://github.com/user-attachments/assets/70d01e15-fe57-48ec-b383-9de67b912b6f)

### RESULT
The program successfully sorts the dictionary by its values in alphabetical order and displays the sorted dictionary.



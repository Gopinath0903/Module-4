# Exp.No:18  
## FILES - FIND AND REPLACE
---

### AIM  
To write a Write a Python function to find and replace a word in a file.

---

### ALGORITHM


1. **Create a File**  
   - Take the file path and content as input.  
   - Open the file in write mode and write the content to it.

2. **Read the File**  
   - Open the file in read mode and return its content.

3. **Find and Replace**  
   - Open the file and read its content.  
   - Replace all occurrences of the old word with the new word.  
   - Write the updated content back to the file.

4. **Print the Updated File Content**  
   - Read the file again and print the result.



### PROGRAM
~~~
Reg no-212223070007
Name-Gopinath G

def create_file(file_path, content):
    with open(file_path, 'w') as file:
        file.write(content)

def read_file(file_path):
    with open(file_path, 'r') as file:
        return file.read()

def find_and_replace(file_path, old_word, new_word):
    with open(file_path, 'r') as file:
        content = file.read()
    updated_content = content.replace(old_word, new_word)
    with open(file_path, 'w') as file:
        file.write(updated_content)
~~~




### OUTPUT
![image](https://github.com/user-attachments/assets/4da1b6ae-79ef-48cb-a34c-414be22a2efa)



### RESULT
Thus the Python function to find and replace a word in a file was executed  successfully

# Exp.No:16  
## DICTIONARY - PRIME OR NOT PRIME

---

### AIM  
To write a program in Python that asks the user to enter ten integers of their choice and return them a dictionary whose keys are the entered integers and whose values are 'prime' or 'not prime' depending on the entered integer.

---

### ALGORITHM



1. **Define a function** to check if a number is prime:
   - If the number is less than or equal to 1, return False.
   - Check all numbers from 2 to square root of the number:
     - If the number is divisible by any of them, it's not prime.
   - If no divisors are found, return True.

2. **Create an empty dictionary** to store numbers and their status.

3. **Repeat 10 times**:
   - Ask the user to input a number.
   - Use the prime-check function to check if the number is prime.
   - If it's prime, store it in the dictionary with the value `"prime"`.
   - Otherwise, store it with the value `"not prime"`.

4. **Print the dictionary**.


### PROGRAM

```
#Reg.No-212223070007
#Name-Gopinath G
#Add Your Code Here
def isPrim(n):
    # initializing the number of divisors of n
    numberDivisors = 0
    
    for i in range(1 , n + 1):
        if (n%i==0):
            numberDivisors=numberDivisors+1
    if(numberDivisors==2):
        return True 
    else:
        return False
        
        
d = dict({})
for i in range(0 , 10):
    n=int(input())
    if(isPrim(n)):
        d[n]="prime"
    else:
        d[n]="not prime"
print(d)


```

### OUTPUT
![image](https://github.com/user-attachments/assets/3fcd0433-318c-4a32-b0e7-8ec81ab40f52)


### RESULT
Thus the Program in Python that asks the user to enter ten integers of their choice and return them a dictionary whose keys are the entered integers and whose values are 'prime' or 'not prime' depending on the entered integer was executed  successfully


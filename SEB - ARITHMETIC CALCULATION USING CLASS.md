# Exp.No:20  
## SEB - ARITHMETIC CALCULATION USING CLASS

---

### AIM  
To write a python program to perform multiplication and floor division operation using class and if,elif..note:

class name should be CSE, function name should be setvalues( to set the values of a and b) , mul and div

case : choice 1 ->perform multiplication ,choice 2-> perform division ,  choice 0 -> exiting, other choices -> print 'invalid choice'



---

### ALGORITHM

1. Read two numbers `a` and `b` from the user.  
2. Calculate `a * b` and store it as multiplication result.  
3. Calculate `a / b` (integer division) and store it as division result.  
4. Read a number `n` from the user as a choice.  
5. If `n` is less than 0 or greater than 2:  
   - Print `"Invalid choice"`.  
6. If `n` is 1:  
   - Print the multiplication result.  
7. If `n` is 2:  
   - Print the division result.  
8. Print `"Exiting!"`.



### PROGRAM

```
Reg no-212223070007
Name-Gopinath G

a=int(input())
b=int(input())
add=a*b
div=int(a/b)
n=int(input())
if n<0 or n>2:
    print("Invalid choice")
elif n==1:
    print(f"Result:  {add}")
elif n==2:
    print(f"Result:  {div}")
print("Exiting!")



```

### OUTPUT

![image](https://github.com/user-attachments/assets/e978d748-03f5-485b-8bd5-07460f3e8d49)

### RESULT
Thus the python program to perform multiplication and floor division operation using class and if,elif..note:

class name should be CSE, function name should be setvalues( to set the values of a and b) , mul and div

case : choice 1 ->perform multiplication ,choice 2-> perform division ,  choice 0 -> exiting, other choices -> print 'invalid choice'
was executed successfully

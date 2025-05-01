# Exp.No:17  
## EXCEPTION HANDLING

---

### AIM  
 Write a python program for solving following error using exception handling 

---

### ALGORITHM


1. Create an empty list called `lst`.

2. Read an integer `num` from the user.

3. Repeat the following steps `num` times:
   - Read an integer from the user.
   - Add (append) it to the list `lst`.

4. Try to do the following:
   - Print the entire list.
   - Print the value at index 6 of the list.

5. If index 6 does not exist, print `"6 is not accepted"`.


### PROGRAM

```
Reg.No-212223070007
Name-Gopinath G
Add Your Code Here
lst=[]
def index():
    for i in range(num):
        n=int(input())
        lst.append(n)
num=int(input())
index()
try:
    print(lst)
    print(lst[6])
except:
    print("6 is not accepted")
```

### OUTPUT
![image](https://github.com/user-attachments/assets/86668301-0c2f-45e4-beaf-fa93d6710b0c)


### RESULT
Thus the python program for solving following error using exception handling was executed successfully

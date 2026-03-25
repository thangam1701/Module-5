# Exp.No:22  
## Destructor

### AIM  
To create a Python class `Student` with a destructor.


### ALGORITHM

1. Begin the program.  
2. Define the `student` class.  
3. Inside the `student` class, define the `__init__` method (constructor) and the `__del__` method (destructor).  
4. Create an object `s2` of the `student` class. When the object `s2` is created, the `__init__` method is called, and its print statements are executed.  
5. Use the `del` statement to delete the object `s2`. This triggers the `__del__` method (destructor), and the respective print statements are executed.  
6. Terminate the program.

---

### PROGRAM

```
class fid:
    def __init__(self):
        print("Employee created.")
    def __del__(self):
        
        print("Destructor called, Employee deleted.")
fid()
```

### OUTPUT
![image](https://github.com/user-attachments/assets/4a805d99-d007-4980-8176-81dee48d6d83)


### RESULT
Thus a Python class Student with a destructor was implemented and executed.

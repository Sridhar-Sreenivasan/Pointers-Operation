# Pointer-Operations-In-Cpp

---

## Aim  
To understand and implement the concept of **functions in C++** using:  
1. Call by Value  
2. Call by Reference (Swap)  
3. Call by Reference with Increment  

---

## Theory  

- **Function:** A block of code designed to perform a specific task.  
- **Call by Value:** A method of passing arguments where the actual value is copied into the function’s parameter. Changes inside the function **do not affect** the original variables.  
- **Call by Reference:** A method of passing arguments where the reference (memory address) is passed. Changes inside the function **directly affect** the original variables.  
- **Increment (using reference):** Demonstrates how reference can be used to modify values of variables by adding a fixed constant or input.  

### Key Differences  
- Call by Value → Works on copies of data.  
- Call by Reference → Works on original data.  

---

## Algorithm  

### Experiment 10A – Swap using Call by Value  
1. Start the program.  
2. Define a function `swap(a, b)` with parameters passed **by value**.  
3. Inside the function, swap the values of `a` and `b`.  
4. Display values inside the function.  
5. Show original values in `main()` (unchanged).  
6. End.  

---

### Experiment 10B – Swap using Call by Reference  
1. Start the program.  
2. Define a function `swap(a, b)` with parameters passed **by reference**.  
3. Inside the function, swap the values of `a` and `b`.  
4. Display values inside the function.  
5. Show values in `main()` (changed).  
6. End.  

---

### Experiment 10C – Increment using Call by Reference  
1. Start the program.  
2. Define a function `increment(x)` where parameter is passed **by reference**.  
3. Inside the function, add a fixed number `a` to `x`.  
4. Display the updated result.  
5. End.  

# Conclusion (Experiment 10)  
- Learned the **difference between Call by Value and Call by Reference** in C++.  
- Verified that in **Call by Value**, original values remain unchanged.  
- Verified that in **Call by Reference**, changes reflect in the actual variables.  
- Understood how to use **reference variables** for incrementing and updating data directly.  
- Experiment successfully demonstrated the **importance of parameter passing methods** in C++.  

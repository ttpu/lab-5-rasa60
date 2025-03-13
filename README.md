# CS Lab-5 template
---

## Exercise 1  

### Problem Statement  

Write a Python program to:  

- Load an array `v` consisting of `N` positive integer numbers (`N` being a predefined constant).  
- Display on the first line all the elements of the array that are odd.  
- Display on the second line all the elements of the array that are even.  

### Example  

Let `N = 10`, and assume that the following array has been introduced:  

v = [4, 6, 5, 2, 8, 11, 10, 9, 28, 3]


Then, the program should produce the following output:  

Odd numbers: 5 11 9 3 \
Even numbers: 4 6 2 8 10 28

---

## Exercise 2  

### Problem Statement  

Write a Python program that:  

1. Reads a positive integer number `n` (whose value is at most 100).  
2. Loads an array `v` of `n` integer numbers.  
3. Reads an integer number `x`.  
4. Determines and prints out how many times value `x` appears in the `v` array.  
5. Asks the user whether they want to repeat the search with another value:  
   - If yes, the program restarts from point 3.  
   - Otherwise, it terminates.  

### Example  

The following is a possible execution of the program (underlined text is typed by the user):  


Input n: 5 \
Input v[0]: 4 \
Input v[1]: 0 \
Input v[2]: -1 \
Input v[3]: 4 \
Input v[4]: 2 

Input x: 4 \
Value 4 appears 2 time(s) in the array. \
Would you like to continue (1=yes, 0=no)? 1 

Insert x: 3 \
Value 3 appears 0 time(s) in the array. \
Would you like to continue (1=yes, 0=no)? 1 

Insert x: 2 \
Value 2 appears 1 time(s) in the array. \
Would you like to continue (1=yes, 0=no)? 0 

Program terminated.

---

## Exercise 3  

### Problem Statement  

Write a Python program that:  

- Loads two arrays `v` and `w`, each containing 10 integer numbers.  
- Finds the position `i` where the absolute value of the difference between the corresponding elements `v[i]` and `w[i]` is maximum.  
- Prints out the position `i` and the value of this maximum difference.  

### Example  

Let the contents of the two arrays be:  

v = [5, 1, 7, 9, 11, 13, 2, 17, 19, 21]  \
w = [3, 33, -4, 5, 6, 0, 1, 1, 19, 17]


Then, the program should output:  

The maximum difference (in absolute value) between corresponding elements is found at position 1,
i.e., between numbers 1 and 33, and it evaluates to 32.


---

## Exercise 4  

### Problem Statement  

Write a Python program that:  

- Reads an array named `base` of `N` integer values (`N` is a predefined constant).  
- Reads an array named `exp` of `N` positive integer values.  
- Computes and displays an array named `power`, where each element at position `i` is given by raising the corresponding elements of `base` and `exp` to the power (i.e., `power[i] = base[i] ** exp[i]`).  
- **Note:** Avoid using the built-in `pow()` function to compute the power operation.  

### Example  

Let the contents of the two arrays be:  

base = [1, -2, 3, 4, -5]  \
exp = [4, 3, 2, 3, 2]


Then, the computed and displayed array should be:  

power = [1, -8, 9, 64, 25]

---

## Exercise 5  

### Problem Statement  

Write a Python program that:  

- Loads an array `v` of `DIM` real numbers (`DIM` is a predefined constant).  
- Determines and prints the starting index and the length of the longest sequence of consecutive positive values in the array.  

### Example  

Let `DIM = 11`, and assume the following array has been introduced:  

v = [2.0, 3.1, 4.3, -10.6, -2.0, 5.2, 1.2, 8.9, 3.1, -9.2, 8.3]


Then, the program should output:  

The longest positive sequence (4 elements) starts from index 5.


Explanation:  \
The longest sequence of positive values is:  

5.2 → 1.2 → 8.9 → 3.1

which has **4 elements** and starts at **index 5**.

---








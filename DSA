"""
MODULE: DATA STRUCTURES AND ALGORITHMS (DSA)
Concepts Covered:
- What is DSA?
- Data Structures
- Types of Data Structures
- What is an Algorithm?
- Importance of DSA
- Applications of DSA
- Important DSA Terms
- Fibonacci Series (Theory + Code)
"""

# ============================================
# 1️⃣ WHAT IS DSA?
# ============================================
"""
DSA stands for Data Structures and Algorithms.

- Data Structures → How data is stored and organized.
- Algorithms → Step-by-step methods to solve problems.

In simple words:
DSA teaches how to store data properly and solve problems efficiently.

Real-life Example:
Phone contacts = Data Structure
Searching a contact = Algorithm
"""

print("\n--- WHAT IS DSA? ---")
print("DSA helps store data properly and solve problems efficiently.")

# ============================================
# 2️⃣ WHAT ARE DATA STRUCTURES?
# ============================================
"""
A data structure is a way to store data so that it can be:
- Accessed easily
- Updated quickly
- Used efficiently
"""

print("\n--- DATA STRUCTURES ---")
print("Data structures organize data for easy access and efficient use.")

# ============================================
# 3️⃣ TYPES OF DATA STRUCTURES
# ============================================
"""
1) Primitive Data Structures (Single values)
- int, float, char, boolean

2) Non-Primitive Data Structures (Multiple values)
- Array
- Linked List
- Stack
- Queue
- Tree
- Graph
"""

print("\n--- TYPES OF DATA STRUCTURES ---")
print("Primitive and Non-Primitive data structures store data in different ways.")

# ============================================
# 4️⃣ WHAT IS AN ALGORITHM?
# ============================================
"""
An algorithm is a step-by-step method to solve a problem.

Example (Making Tea Algorithm):
1. Boil water
2. Add tea leaves
3. Add sugar
4. Add milk
5. Boil
6. Serve
"""

print("\n--- ALGORITHM ---")
print("An algorithm is a step-by-step solution to a problem.")

# ============================================
# 5️⃣ WHY IS DSA IMPORTANT?
# ============================================
"""
DSA is important because it helps:
- Solve problems correctly
- Make programs faster
- Use less memory
- Handle large data
- Crack coding interviews
- Build real-world applications
"""

print("\n--- IMPORTANCE OF DSA ---")
print("DSA improves speed, memory usage, and problem-solving skills.")

# ============================================
# 6️⃣ WHERE IS DSA USED?
# ============================================
"""
DSA is used in:
- Operating systems
- Websites and mobile apps
- Databases
- Search engines
- GPS & navigation
- AI & Machine Learning
- Games
- Banking systems
- Social media
"""

print("\n--- APPLICATIONS OF DSA ---")
print("DSA is used in almost every software system.")

# ============================================
# 7️⃣ IMPORTANT DSA TERMS
# ============================================
"""
Algorithm – Steps to solve a problem
Data Structure – Way to store data
Time Complexity – Time taken by algorithm
Space Complexity – Memory used
Big O Notation – Performance representation
Recursion – Function calling itself
Divide and Conquer – Breaking problem into parts
Brute Force – Trying all possible solutions
"""

print("\n--- IMPORTANT DSA TERMS ---")
print("Understanding these terms helps write better programs.")

# ============================================
# 8️⃣ FIBONACCI SERIES (THEORY)
# ============================================
"""
The Fibonacci series is a sequence where:
- First number = 0
- Second number = 1
- Each next number = Sum of previous two

Formula:
F(n) = F(n-1) + F(n-2)

Example:
0, 1, 1, 2, 3, 5, 8, 13, 21, 34, ...
"""

print("\n--- FIBONACCI SERIES ---")
print("Fibonacci series is based on adding the previous two numbers.")

# ============================================
# 9️⃣ WHY FIBONACCI IS IMPORTANT IN DSA?
# ============================================
"""
Fibonacci helps understand:
- Loops
- Recursion
- Time complexity
- Space complexity
- Optimization
- Dynamic programming
"""

print("\n--- IMPORTANCE OF FIBONACCI ---")
print("Fibonacci teaches loops, recursion, and optimization.")

# ============================================
# 🔟 HOW FIBONACCI WORKS (STEP-BY-STEP)
# ============================================
"""
Start:
a = 0
b = 1

Repeat:
next = a + b
a = b
b = next
"""

print("\n--- HOW FIBONACCI WORKS ---")
print("Each number is the sum of the previous two.")

# ============================================
# 1️⃣1️⃣ FIBONACCI USING LOOP (BEST METHOD)
# ============================================
"""
This method is:
- Fast
- Simple
- Uses minimum memory
- Best for interviews and real projects
"""

print("\n--- FIBONACCI USING LOOP ---")

a, b = 0, 1
print(a)
print(b)

for i in range(8):
    a, b = b, a + b
    print(b)

"""
Performance:
Time Complexity: O(n)
Space Complexity: O(1)
"""

# ============================================
# 1️⃣2️⃣ FIBONACCI USING RECURSION (SLOW)
# ============================================
"""
Recursive method:
Easy to understand but slow for large numbers.
"""

print("\n--- FIBONACCI USING RECURSION ---")

def fib_recursive(n):
    if n <= 1:
        return n
    return fib_recursive(n - 1) + fib_recursive(n - 2)

print("Fibonacci of 9:", fib_recursive(9))

"""
Problems:
- Same values are calculated again and again
- Very slow for large n

Performance:
Time Complexity: O(2^n)
Space Complexity: O(n)
"""

# ============================================
# 1️⃣3️⃣ OPTIMIZED FIBONACCI USING LOOP (BEST)
# ============================================
"""
This method finds the nth Fibonacci number efficiently.
Uses loop instead of recursion.
"""

print("\n--- OPTIMIZED FIBONACCI USING LOOP ---")

def fib_optimized(n):
    if n <= 1:
        return n
    a, b = 0, 1
    for i in range(2, n + 1):
        a, b = b, a + b
    return b

print("Fibonacci of 19:", fib_optimized(19))

# ============================================
# 1️⃣4️⃣ FIBONACCI SUMMARY
# ============================================
"""
- Fibonacci series is based on adding the previous two numbers.
- Loop method is fastest and easiest.
- Recursive method is slow but good for learning.
- Always prefer loop or optimized method in real programs.
"""

print("\n--- FIBONACCI SUMMARY ---")
print("Always use loop or optimized method in real-world applications.")

print("\n✅ DSA + FIBONACCI MODULE COMPLETE ✅")

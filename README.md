# 📘 Data Structures & Algorithms: C++ Masterclass Notes



## 🎯 Placement & Interview Strategies
* **Problem Solving:** Think on paper with at least 5 test cases before coding, and code all possible approaches (including brute force)[cite: 7].
* **Mindset:** Focus on accuracy more than speed, and build logic rather than memorizing syntax[cite: 7].
* **Interviews:** Always be prepared to explain the Time and Space complexity after providing a solution, and use `cout` statements if you get confused during coding to understand what is happening[cite: 7].
* **Preparation:** Do documentation of your approaches, track your incorrect/skipped questions, and network with HR or team members for opportunities[cite: 7].

## 💻 C++ Fundamentals & Memory Management
* **Data Types & Storage:** Explains the byte sizes and memory allocation for primitives (e.g., `int` is 4 bytes/32 bits), and how negative numbers are stored using the 2's complement method[cite: 7].
* **Bitwise Operators:** Detailed breakdown of AND, OR, NOT, XOR, and Shift operators, noting that left shift generally multiplies by 2 and right shift divides by 2[cite: 7].
* **Variable Scoping:** Explains local vs. global variables, heavily advising against the use of global variables (marking it as a "BAD PRACTICE")[cite: 7].

## ⏳ Complexity Analysis
* **Notations:** Defines Big-O (upper bound/worst case), Theta (average case), and Omega (lower bound/best case)[cite: 7].
* **Complexity Order:** Ranks complexities from fastest to slowest: $O(1) < O(\log_2 n) < O(\sqrt{n}) < O(n) < O(n \log n) < O(n^2) < O(n^3) < O(2^n) < O(n!)$[cite: 7].

## 🏗️ Data Structures
* **Arrays & 2D Arrays:** Covers continuous memory allocation, 0-based indexing, and 2D array mapping using the formula `linear_index = c * i + j` (where c is the number of columns)[cite: 7].
* **Vectors:** Explains dynamic arrays that double in size when full, including initialization and built-in methods like `push_back` and `pop_back`[cite: 7].
* **Char Arrays & Strings:** Highlights that strings are dynamic char arrays terminated by a NULL character (`\0`), and explains how `cin.getline()` is used to read inputs with spaces[cite: 7].

## 🔍 Algorithms (Searching & Sorting)
* **Searching:** Covers Linear Search ($O(n)$) and Binary Search ($O(\log_2 n)$), including advanced binary search concepts like search spaces, lower/upper bounds, and preventing integer overflow using `mid = s + (e - s) / 2`[cite: 7].
* **Sorting:** Details Selection Sort, Bubble Sort, and Insertion Sort (all $O(n^2)$ worst case), alongside the C++ inbuilt `sort()` function which uses Intro Sort ($O(n \log n)$)[cite: 7].
* **Stability:** Explains stable vs. unstable sorting algorithms, noting that stable sorts (like Bubble and Insertion) preserve the original order of duplicate elements[cite: 7].

## 🧠 Pointers & Reference Variables
* **Symbol Table:** Explains how the operating system maps variable names to memory addresses and data types[cite: 7].
* **Pointers:** Covers pointer creation, dereferencing, pointer arithmetic, and the dangers of dangling/wild pointers leading to segmentation faults[cite: 7].
* **Multi-Level Pointers:** Illustrates double (`**ptr`) and triple pointers mapping to memory addresses[cite: 7].
* **Reference Variables:** Recommends using reference variables (pass by reference) over pointers for better readability and safety, but warns that using "Return by Reference" for local/temporary variables is a bad practice[cite: 7].

## 🧮 Basic Mathematics for DSA
* **Prime Numbers:** Implements the Sieve of Eratosthenes ($O(n \log(\log n))$) to efficiently find primes[cite: 7].
* **GCD/LCM:** Uses Euclid's Algorithm to find the Greatest Common Divisor, and the relationship formula `LCM = (a * b) / GCD`[cite: 7].
* **Fast Exponentiation:** Optimizes power calculations to $O(\log n)$[cite: 7].

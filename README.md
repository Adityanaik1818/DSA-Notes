<div align="center">

<!-- Animated Header Wave -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=8A2BE2&height=250&section=header&text=DSA%20C++%20Masterclass&fontSize=60&fontAlignY=35&animation=twinkling&fontColor=ffffff&desc=Handwritten%20Notes%20&descAlignY=55&descAlign=50" width="100%" />

<!-- Animated Typing Text -->
<img src="https://readme-typing-svg.herokuapp.com/?lines=Data+Structures+and+Algorithms;C%2B%2B+Fundamentals+%26+Memory;Interview+%26+Placement+Preparation;Problem+Solving+%26+Logic+Building&center=true&width=600&height=50&color=8A2BE2&vCenter=true&size=20" />

<p align="center">
  <a href="https://github.com/Adityanaik1818">
    <img src="https://img.shields.io/badge/Author-Aditya%20Prakash%20Naik-8A2BE2?style=for-the-badge&logo=github&logoColor=white" alt="Author">
  </a>
  <img src="https://img.shields.io/badge/Language-C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++">
  <img src="https://img.shields.io/badge/Focus-Interview%20Prep-FF9900?style=for-the-badge&logo=leetcode&logoColor=white" alt="Prep">
</p>

<h3>
  <a href="./DSA%20Handwritten%20Notes.pdf">
    <kbd>📕 VIEW FULL HANDWRITTEN PDF</kbd>
  </a>
</h3>

</div>

---

## 🌟 Vision & Strategy

<table align="center" width="100%">
  <tr>
    <td width="50%" align="center">
      <h3>🧠 The Mindset</h3>
      <p align="left">Focus on accuracy more than speed, and build logic rather than memorizing syntax[cite: 7]. Think on paper with at least 5 test cases before coding, and code all possible approaches including brute force[cite: 7].</p>
    </td>
    <td width="50%" align="center">
      <h3>🎯 The Execution</h3>
      <p align="left">Always be prepared to explain the Time and Space complexity after providing a solution[cite: 7]. Document your approaches, track your skipped questions, and network with HR or team members for opportunities[cite: 7].</p>
    </td>
  </tr>
</table>

---

## 🚀 Core Architecture

### 💻 C++ Fundamentals & Memory Management
> *Understanding how the machine thinks.*
* **Data Types & Storage:** Primitive types rely on specific byte sizes (e.g., `int` is 4 bytes/32 bits), with negative numbers stored using the 2's complement method[cite: 7].
* **Bitwise Operators:** Left shifts generally multiply by 2, while right shifts divide by 2[cite: 7]. 
* **Variable Scoping:** Global variables are heavily advised against and marked as a strict "BAD PRACTICE"[cite: 7].

### ⏳ Complexity Analysis
> *Evaluating algorithm efficiency.*
* **Notations:** Big-O evaluates the upper bound/worst case, Theta evaluates the average case, and Omega evaluates the lower bound/best case[cite: 7].
* **Complexity Order:** Ranked from fastest to slowest: `O(1)` < `O(log n)` < `O(√n)` < `O(n)` < `O(n log n)` < `O(n^2)` < `O(n^3)` < `O(2^n)` < `O(n!)`[cite: 7].

---

## 🏗️ Data Structures Arsenal

<div align="center">

| Structure | Memory & Indexing | Operations & Nuances |
| :--- | :--- | :--- |
| **Arrays & 2D Arrays** | Continuous memory allocation with 0-based indexing[cite: 7]. | 2D arrays map linearly using the formula `linear_index = c * i + j` (where c = columns)[cite: 7]. |
| **Vectors** | Dynamic arrays that double in size when full[cite: 7]. | Utilizes built-in methods like `push_back` and `pop_back` for dynamic manipulation[cite: 7]. |
| **Char Arrays & Strings** | Strings are dynamic char arrays terminated by a NULL character (`\0`)[cite: 7]. | Read inputs with spaces smoothly using `cin.getline()`[cite: 7]. |

</div>

---

## ⚡ Algorithms Matrix

### 🔍 Searching
* **Linear Search:** `O(n)` complexity[cite: 7].
* **Binary Search:** `O(log n)` complexity[cite: 7]. 
  * *Pro-Tip:* Prevent integer overflow by calculating the midpoint as `mid = s + (e - s) / 2`[cite: 7]. 

### 🔀 Sorting
* **Standard Sorts:** Selection, Bubble, and Insertion Sorts all operate at `O(n^2)` worst-case time[cite: 7].
* **Intro Sort:** The C++ inbuilt `sort()` function operates at `O(n log n)`[cite: 7].
* **Stability:** Stable sorts (like Bubble and Insertion) preserve the original order of duplicate elements[cite: 7].

---

## 🧠 Advanced Memory: Pointers & References

### 1. The Symbol Table & Pointers
The operating system maps variable names to memory addresses and data types using a Symbol Table[cite: 7]. Pointers require careful management; dangling or wild pointers will lead to severe segmentation faults[cite: 7].

### 2. Multi-Level Architecture
Mastering double (`**ptr`) and triple pointers allows for complex mapping directly to nested memory addresses[cite: 7].

### 3. Reference Variables
Using reference variables (pass by reference) is recommended over pointers for better readability and safety[cite: 7]. 
> ⚠️ **Warning:** Using "Return by Reference" for local or temporary variables is a bad practice and causes memory leaks[cite: 7].

---

## 🧮 Applied Mathematics for DSA

<table>
  <tr>
    <td align="center"><b>🔢 Prime Numbers</b></td>
    <td>Implement the <b>Sieve of Eratosthenes</b> <code>O(n log(log n))</code> to efficiently find primes[cite: 7].</td>
  </tr>
  <tr>
    <td align="center"><b>➗ GCD & LCM</b></td>
    <td>Use <b>Euclid's Algorithm</b> to find the GCD, and apply the formula <code>LCM = (a * b) / GCD</code>[cite: 7].</td>
  </tr>
  <tr>
    <td align="center"><b>⚡ Fast Exponentiation</b></td>
    <td>Optimize heavy power calculations down to <code>O(log n)</code> time complexity[cite: 7].</td>
  </tr>
</table>

---

<!-- Animated Footer -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=8A2BE2&height=100&section=footer" width="100%" />
  <br>
  <i>Keep Coding • Keep Learning • Keep Growing</i>
  <br><br>
  <b>Developed & Maintained by Aditya Prakash Naik</b>
</div>

<div align="center">

<!-- Futuristic Animated Header -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00c8ff,100:ff00c8&height=280&section=header&text=C%2B%2B%20DSA%20Masterclass&fontSize=65&fontAlignY=35&animation=twinkling&fontColor=ffffff&desc=The%20Ultimate%20Handwritten%20Playbook&descAlignY=55&descAlign=50" width="100%" />

<!-- Animated Neon Typing Text -->
<img src="https://readme-typing-svg.herokuapp.com/?lines=►+Data+Structures+%26+Algorithms;►+C%2B%2B+Fundamentals+%26+Memory;►+Cracking+The+Coding+Interview;►+Optimizing+Time+%26+Space+Complexity&center=true&width=600&height=60&color=00c8ff&vCenter=true&size=22&font=Fira+Code" />

<br>

<p align="center">
  <a href="https://github.com/Adityanaik1818">
    <img src="https://img.shields.io/badge/Architect-Aditya%20Naik-000000?style=for-the-badge&logo=github&logoColor=00c8ff" alt="Author">
  </a>
  <img src="https://img.shields.io/badge/Language-C++-000000?style=for-the-badge&logo=c%2B%2B&logoColor=ff00c8" alt="C++">
  <img src="https://img.shields.io/badge/Focus-Placements-000000?style=for-the-badge&logo=leetcode&logoColor=00c8ff" alt="Prep">
</p>

<br>

<a href="./DSA%20Handwritten%20Notes.pdf">
  <img src="https://img.shields.io/badge/📖_OPEN_FULL_HANDWRITTEN_PDF-000000?style=for-the-badge&logo=adobeacrobatreader&logoColor=ff00c8" alt="Read PDF" width="400">
</a>

</div>

---

<br>

<h2 align="center">✦ THE DEVELOPER'S MINDSET ✦</h2>

<table align="center" width="100%">
  <tr>
    <td width="50%" align="center">
      <br>
      <img src="https://img.icons8.com/nolan/64/brain.png" width="50"/><br>
      <b>Logic > Syntax</b><br>
      <br>
      <p align="left">
        Focus on accuracy more than speed, and build logic rather than memorizing syntax[cite: 7]. Think on paper with at least 5 test cases before coding, and map out all approaches including brute force[cite: 7].
      </p>
    </td>
    <td width="50%" align="center">
      <br>
      <img src="https://img.icons8.com/nolan/64/interview.png" width="50"/><br>
      <b>Interview Tactics</b><br>
      <br>
      <p align="left">
        Always explain Time & Space complexity immediately after providing a solution[cite: 7]. Document your approaches, track skipped questions, and network with HR/team members for real opportunities[cite: 7].
      </p>
    </td>
  </tr>
</table>

<br>

---

<h2 align="center">✦ CORE ARCHITECTURE ✦</h2>

### 💻 C++ Fundamentals & Memory Management
> _Decoding how the machine operates at the lowest level._
* **Data Types & Storage:** Primitives rely on strict byte sizes (e.g., `int` is 4 bytes/32 bits)[cite: 7]. Negative numbers are processed using the 2's complement method[cite: 7].
* **Bitwise Operations:** Left shifts multiply by 2; right shifts divide by 2[cite: 7]. 
* **Scoping Rule:** Global variables are strictly marked as a **BAD PRACTICE**—avoid them entirely[cite: 7].

### ⏳ Complexity Analysis
> _The true metric of algorithm efficiency._
* **Notations:** 
  * **Big-O** (Upper Bound / Worst Case)[cite: 7]
  * **Theta** (Average Case)[cite: 7]
  * **Omega** (Lower Bound / Best Case)[cite: 7]
* **Speed Hierarchy:** `O(1)` < `O(log n)` < `O(√n)` < `O(n)` < `O(n log n)` < `O(n^2)` < `O(n^3)` < `O(2^n)` < `O(n!)`[cite: 7].

<br>

---

<h2 align="center">✦ DATA STRUCTURES ARSENAL ✦</h2>

| <div align="center">🚀 Structure</div> | <div align="center">🧠 Memory & Behavior</div> |
| :--- | :--- |
| <kbd>⊞ Arrays & 2D</kbd> | Continuous memory allocation with 0-based indexing[cite: 7]. 2D arrays map linearly using the formula `linear_index = c * i + j` (where c = columns)[cite: 7]. |
| <kbd>⟳ Vectors</kbd> | Dynamic arrays that seamlessly double in size when full, utilizing built-in methods like `push_back` and `pop_back`[cite: 7]. |
| <kbd>✎ Char Arrays</kbd> | Strings operate as dynamic char arrays terminated by a NULL character (`\0`)[cite: 7]. Use `cin.getline()` to read spaced inputs flawlessly[cite: 7]. |

<br>

---

<h2 align="center">✦ ALGORITHMIC MASTERY ✦</h2>

<table align="center" width="100%">
  <tr>
    <td width="50%">
      <h3 align="center">🔍 Searching</h3>
      <blockquote>
        <b>Linear Search:</b> <code>O(n)</code> time[cite: 7].<br><br>
        <b>Binary Search:</b> <code>O(log n)</code> time[cite: 7].<br>
        <i>⚠️ Pro-Tip:</i> Prevent integer overflow by calculating the midpoint precisely as <code>mid = s + (e - s) / 2</code>[cite: 7].
      </blockquote>
    </td>
    <td width="50%">
      <h3 align="center">🔀 Sorting</h3>
      <blockquote>
        <b>Standard:</b> Selection, Bubble, and Insertion Sorts hit <code>O(n^2)</code> worst-case[cite: 7].<br><br>
        <b>Intro Sort:</b> The C++ inbuilt <code>sort()</code> runs at <code>O(n log n)</code>[cite: 7].<br><br>
        <b>Stability:</b> Stable algorithms (Bubble/Insertion) preserve the order of duplicate elements[cite: 7].
      </blockquote>
    </td>
  </tr>
</table>

<br>

---

<h2 align="center">✦ ADVANCED MEMORY: POINTERS & MATH ✦</h2>

### 🔗 Pointers & The Symbol Table
* **The Symbol Table:** The OS maps variable names to exact memory addresses and data types[cite: 7].
* **Multi-Level Architecture:** Master double (`**ptr`) and triple pointers for deep nested memory manipulation[cite: 7].
* **Reference Variables:** Pass by reference is significantly safer and more readable than raw pointers[cite: 7]. 
* 🚨 **Red Flag:** Using "Return by Reference" for local or temporary variables is a critical bad practice[cite: 7].

### 🧮 Applied DSA Mathematics
* **Prime Numbers:** Deploy the **Sieve of Eratosthenes** `O(n log(log n))` for extreme efficiency[cite: 7].
* **GCD & LCM:** Utilize **Euclid's Algorithm** for GCD, and bridge it using `LCM = (a * b) / GCD`[cite: 7].
* **Fast Exponentiation:** Compress massive power calculations down to `O(log n)` time complexity[cite: 7].

<br>

---

<!-- Animated Footer -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:ff00c8,100:00c8ff&height=120&section=footer" width="100%" />
  <br>
  <code>&lt; Keep Coding /&gt;</code> <code>&lt; Keep Learning /&gt;</code> <code>&lt; Keep Growing /&gt;</code>
  <br><br>
  <b>Developed & Maintained by <a href="https://github.com/Adityanaik1818">Aditya Prakash Naik</a></b>
</div>

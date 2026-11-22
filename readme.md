# Analysis and Design of Algorithms Lab (BT CS 505A)

**Department of Computer Science and Engineering**  
**Central University of Haryana (CUH)**  
*Jant-Pali, Mahendergarh, Haryana - 123031*

---

### Student Details
- **Name:** Shaik Akthar
- **Roll Number:** 241493
- **Course:** B.Tech Computer Science and Engineering
- **Semester:** 5th Semester
- **Lab Instructor:** Mr. Anant R. Bara *(Assistant Professor, Department of CSE)*
- **Compiled Report:** [main.pdf](main.pdf)

---

## Lab Programs Index

| # | Program Name | Source File | Description |
|---|---|---|---|
| **01** | Binary Search & Fast Power | [`program1.py`](program1.py) | Search in Rotated Sorted Array & Binary Exponentiation ($O(\log n)$) |
| **02** | Divide & Conquer Sorting | [`program2.py`](program2.py) | Merge Sort and Quick Sort implementations with pivot partitioning |
| **03** | Order Statistics & Min-Max | [`program3.py`](program3.py) | $K$-th largest element in array and simultaneous Min-Max search |
| **04** | Strassen's Matrix Multiplication | [`program4.py`](program4.py) | Divide-and-conquer $2 \times 2$ matrix multiplication via 7 multiplications |
| **05** | Greedy: Knapsack & Job Sequencing | [`program5.py`](program5.py) | Fractional Knapsack (greedy by ratio) & Job Sequencing with Deadlines |
| **06** | Minimum Spanning Tree (MST) | [`program6.py`](program6.py) | Prim's Algorithm & Kruskal's Algorithm with Disjoint Set Union (DSU) |
| **07** | Shortest Paths | [`program7.py`](program7.py) | Dijkstra's Single-Source & Bellman-Ford (negative cycle detection) |
| **08** | Huffman Coding | [`program8.py`](program8.py) | Lossless data compression using greedy min-heap prefix-free tree |
| **09** | 0/1 Knapsack & Subset Sum | [`program9.py`](program9.py) | Dynamic Programming solutions for bounded 0/1 Knapsack & Subset Sum |
| **10** | Longest Common Subsequence (LCS) | [`program10.py`](program10.py) | DP table construction and backtracking to reconstruct the optimal LCS |
| **11** | Matrix Chain Multiplication (MCM) | [`program11.py`](program11.py) | Optimal parenthesization minimizing scalar multiplications |
| **12** | All-Pairs Shortest Path & OBST | [`program12.py`](program12.py) | Floyd-Warshall Algorithm & Optimal Binary Search Tree (OBST) |
| **13** | Traveling Salesperson Problem (TSP) | [`program13.py`](program13.py) | Dynamic programming with bitmask state compression |
| **14** | Backtracking: N-Queens | [`program14.py`](program14.py) | Safe placement of $N$ queens on an $N \times N$ chessboard |
| **15** | Graph Coloring & Hamiltonian Cycle | [`program15.py`](program15.py) | Backtracking algorithms for $m$-coloring and Hamiltonian cycle |
| **16** | String Matching & Reservoir Sampling | [`program16.py`](program16.py) | Rabin-Karp rolling hash matching & Reservoir stream sampling |

---

## Directory Structure

```text
├── Images/                 # CUH logo & terminal output screenshots
├── Layout/
│   ├── headerfooter.tex    # LaTeX running header and footer styles
│   └── titlepage.tex       # Official University cover page
├── media/                  # Authentic dark terminal execution captures
├── programs/               # Source programs directory
├── Sections/
│   ├── program-1.tex       # LaTeX section files for Programs 1 - 16
│   └── ...
├── program1.py - 16.py     # Python source code files (executable)
├── main.tex                # Root LaTeX compilation document
├── main.pdf                # Fully compiled 42-page laboratory report
└── readme.md               # Project documentation
```

---

## Compilation

To compile the LaTeX lab manual locally with XeLaTeX:
```bash
xelatex main.tex
xelatex main.tex
```
*(Run twice to update the table of contents and QR codes).*

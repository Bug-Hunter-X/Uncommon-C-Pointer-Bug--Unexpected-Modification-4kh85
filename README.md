# Uncommon C Pointer Bug: Unexpected Modification

This repository demonstrates a subtle bug in C code related to pointer manipulation. The code appears simple but hides a potential pitfall for those less familiar with pointers. 

## Bug Description
The `bug.c` file contains a program that initializes an integer variable `x`, then modifies its value indirectly through a pointer. While this seems straightforward, the code's behavior might be unexpected to those unfamiliar with how pointers modify the underlying data.

## Solution
The `bugSolution.c` file presents a solution that addresses the potential issue, illustrating good practices in pointer usage. The solution highlights the importance of careful pointer manipulation to avoid unintended consequences.

## How to Run
1. Compile the code using a C compiler (like GCC):
   ```bash
   gcc bug.c -o bug
   gcc bugSolution.c -o bugSolution
   ```
2. Run the executable:
   ```bash
   ./bug
   ./bugSolution
   ```
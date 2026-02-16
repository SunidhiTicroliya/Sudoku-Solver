## 🧩 Sudoku Solver (Java)

This project is a **Sudoku Solver** implemented in Java that automatically solves a 9×9 Sudoku puzzle using a **recursive backtracking algorithm**.  
The solver fills empty cells while ensuring all Sudoku rules are satisfied.

---

### 🚀 Features
- Solves standard **9×9 Sudoku puzzles**
- Uses **backtracking** to explore valid number placements
- Validates **rows, columns, and 3×3 subgrids** before inserting numbers
- Detects and reports **unsolvable Sudoku boards**
- Prints the solved board in a clean, readable format

---

### 🛠 How It Works
1. The program scans the board to find an empty cell (represented by `0`).
2. It tries numbers from 1 to 9 in that cell.
3. Before placing a number, it checks:
   - The current row
   - The current column
   - The corresponding 3×3 subgrid
4. If the placement is valid, the algorithm moves to the next empty cell.
5. If no valid number is found, it **backtracks** and tries a different value.

---

### ▶️ How to Run
1. Clone the repository  
   ```bash
   git clone https://github.com/your-username/SudokuSolver.git

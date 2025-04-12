# 🧩 Sudoku Solver (Backtracking Algorithm)

This project provides a programmatic way to solve any standard 9x9 Sudoku puzzle using recursion and backtracking. It checks for valid number placements and fills the board step-by-step until the solution is found.

---

## 📌 Features

- ✅ Solves any valid 9x9 Sudoku board
- ✅ Uses a clean and readable backtracking algorithm
- ✅ Validates number placements (row, column, subgrid)
- ✅ Uses NumPy for neat board display

---

## 🧠 How It Works

1. The program searches for the next empty cell (represented by `0`).
2. It tries numbers from `1` to `9` in that cell.
3. For each number, it checks:
   - Row validity
   - Column validity
   - 3x3 subgrid validity
4. If a number is valid, it's temporarily placed, and the algorithm recurses.
5. If no valid number leads to a solution, it backtracks.

---

## 🧾 Requirements

- Python 3.x  
- NumPy  

Install NumPy using:

```bash
pip install numpy
```

---

## 🚀 Run the Solver

```bash
python sudoku_solver.py
```

---

## 📁 File Structure

```
SudokuSolver/
├── sudoku_solver.py    # Main script with board and solver logic
└── README.md           # Project documentation
```

---

## 🧪 Example Board (Unsolved)
```python
[
 [5,3,0,0,7,0,0,0,0],
 [6,0,0,1,9,5,0,0,0],
 [0,9,8,0,0,0,0,6,0],
 [8,0,0,0,6,0,0,0,3],
 [4,0,0,8,0,3,0,0,1],
 [7,0,0,0,2,0,0,0,6],
 [0,6,0,0,0,0,2,8,0],
 [0,0,0,4,1,9,0,0,5],
 [0,0,0,0,8,0,0,7,9]
]
```

---


## 👨‍💻 Author

Made with ❤️ by [**Yash Raj**](https://github.com/Yash-Raj-96)

---

## 📄 License

MIT License – Free to use and modify.

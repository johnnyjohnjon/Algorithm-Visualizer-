# Sudoku generator and solver


General puzzle 

```python
generate_sudoku(mask_rate=0.7)

"""
[[1 0 0 5 0 0 0 0 3]
 [0 3 7 0 0 1 0 0 4]
 [0 0 0 0 0 2 0 0 0]
 [0 0 0 0 9 4 0 0 0]
 [0 0 4 0 0 0 0 3 2]
 [0 0 0 3 2 5 0 0 0]
 [0 0 0 0 0 0 2 0 0]
 [7 4 0 0 0 0 0 0 0]
 [8 0 0 0 0 3 1 0 0]]
"""
```

Solve by using `solver()` function

```python
solved = solve(puzzle)

"""
[[1 2 8 5 4 7 6 9 3]
 [6 3 7 9 8 1 5 2 4]
 [4 9 5 6 3 2 7 1 8]
 [2 1 3 7 9 4 8 5 6]
 [5 7 4 1 6 8 9 3 2]
 [9 8 6 3 2 5 4 7 1]
 [3 5 1 4 7 6 2 8 9]
 [7 4 2 8 1 9 3 6 5]
 [8 6 9 2 5 3 1 4 7]]
"""
```

you can validate it by following function:

```python
check_solution(your_puzzle)
# Checked: OK
```

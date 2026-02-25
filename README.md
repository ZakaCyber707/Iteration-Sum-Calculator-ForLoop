# CPP Sum Accumulator (For Loop)


## 📖 Overview
This repository showcases an **Accumulation Algorithm**. It calculates the sum of all natural numbers up to a user-defined limit, demonstrating efficient use of assignment operators within a loop.

## ⚙️ Logic Architecture
The program follows a linear accumulation path:
1. **Input:** The user provides an upper limit (`num`).
2. **Iteration:** A `for` loop runs from 1 to `num`.
3. **Accumulation:** In each step, the current value is added to a `sum` variable (`sum = sum + i`).
4. **Final Output:** The program prints the individual numbers and then the total sum.


## 🛠️ Features
* **Iterative Processing:** Efficiently handles ranges without manual calculation.
* **State Management:** Correctly initializes the `sum` variable to `0` to ensure accurate mathematical results.

## 💻 How to Run
1. **Compile:** `g++ Iterative_Sum_Logic.cpp -o SumAccumulator`
2. **Run:** `./SumAccumulator`

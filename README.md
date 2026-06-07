# Algorithms & Problem Solving - Level 3 (C++) 🚀

Welcome to the **Algorithms & Problem Solving - Level 3** repository! This project is dedicated to mastering advanced problem-solving concepts using C++. It contains solutions to various structural, matrix manipulation, string processing, and date-time calculation problems.

---

## 📂 Project Structure

All source files are organized inside the [code](file:///home/nooreldean/Downloads/Algorithms-Problem-Solving-Level-3-main/code/) directory:
- **`1.cpp` to `5.cpp`**: Implemented solutions for matrix creation, row/column summation, and array storage.
- **`6.cpp` to `51.cpp`**: Boilerplate templates set up for upcoming problems.

### 📝 Solved Problems Index

| File | Problem Description | Concepts Covered |
| :--- | :--- | :--- |
| [1.cpp](file:///home/nooreldean/Downloads/Algorithms-Problem-Solving-Level-3-main/code/1.cpp) | Generate a random 3x3 matrix and print it. | 2D Arrays, `rand()`, Formatting with `<iomanip>` |
| [2.cpp](file:///home/nooreldean/Downloads/Algorithms-Problem-Solving-Level-3-main/code/2.cpp) | Generate a random 3x3 matrix and print the sum of each row. | Nested loops, Row accumulation |
| [3.cpp](file:///home/nooreldean/Downloads/Algorithms-Problem-Solving-Level-3-main/code/3.cpp) | Sum matrix rows and store them in a 1D array, then print it. | Pass-by-reference, Array data transfer |
| [4.cpp](file:///home/nooreldean/Downloads/Algorithms-Problem-Solving-Level-3-main/code/4.cpp) | Generate a random 3x3 matrix and print the sum of each column. | Column-wise matrix traversal |
| [5.cpp](file:///home/nooreldean/Downloads/Algorithms-Problem-Solving-Level-3-main/code/5.cpp) | Sum matrix columns and store them in a 1D array, then print it. | Column-wise accumulation, Array storage |

---

## 🛠️ How to Compile & Run

To compile and run any of the C++ files, you can use the GNU Compiler (`g++`) on Linux/macOS or MinGW on Windows:

```bash
# 1. Navigate to the code directory
cd code

# 2. Compile the desired program (e.g., 1.cpp)
g++ -std=c++17 1.cpp -o 1_solution

# 3. Run the executable
./1_solution
```

---

## 🌟 Best Practices Applied

1. **Modular Code Design**: The code is separated into dedicated functions for each task (e.g., `fillmatrixwithrandomnumbers`, `printmatrix`, `rowsum`), promoting clean and readable code.
2. **Proper Formatting**: Output alignment is clean and well-structured using `std::setw` from the `<iomanip>` library.
3. **Pass-by-Reference**: Efficient handling of arrays and matrices by passing them to functions without unnecessary copying.

---

## 📈 Suggested Improvements

Here are some modern C++ practices that could elevate the codebase:

* **Use Modern C++ Random Library**:
  Instead of C-style `rand()` and `srand(time(NULL))`, use the `<random>` header introduced in C++11 (e.g., `std::mt19937` and `std::uniform_int_distribution`) for better distribution and security.
* **Avoid `using namespace std;` globally**:
  In larger codebases, using the entire `std` namespace globally can cause name collisions. It is better to use specific namespaces (e.g., `std::cout`, `std::endl`) or limit it to local scopes.
* **Add a `.gitignore`**:
  Exclude compiled executables and binary files from being tracked by git.

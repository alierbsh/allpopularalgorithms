# 🧠 All Popular Sorting Algorithms in Python

This repository contains clean Python implementations of the most popular sorting algorithms, designed to help you learn, understand, and practice their logic and performance characteristics.

## 🎯 Purpose

- Understand how each sorting algorithm works — step by step
- Implement them from scratch in Python for deep learning
- Analyze their **time complexity (Big O)** and **space usage**
- Optionally visualize and compare their performance

## 📚 Included Algorithms

| Algorithm         | Best Case     | Average Case     | Worst Case         | Space Complexity |
|------------------|---------------|------------------|--------------------|------------------|
| Quick Sort       | O(n log n)    | O(n log n)       | O(n²)              | O(log n)         |
| Merge Sort       | O(n log n)    | O(n log n)       | O(n log n)         | O(n)             |
| Timsort          | O(n)          | O(n log n)       | O(n log n)         | O(n)             |
| Heap Sort        | O(n log n)    | O(n log n)       | O(n log n)         | O(1)             |
| Bubble Sort      | O(n)          | O(n²)            | O(n²)              | O(1)             |
| Insertion Sort   | O(n)          | O(n²)            | O(n²)              | O(1)             |
| Selection Sort   | O(n²)         | O(n²)            | O(n²)              | O(1)             |
| Tree Sort        | O(n log n)    | O(n log n)       | O(n²)              | O(n)             |
| Shell Sort       | O(n log n)    | O(n(log n)²)     | O(n(log n)²)       | O(1)             |
| Bucket Sort      | O(n + k)      | O(n + k)         | O(n²)              | O(n + k)         |
| Radix Sort       | O(nk)         | O(nk)            | O(nk)              | O(n + k)         |
| Counting Sort    | O(n + k)      | O(n + k)         | O(n + k)           | O(k)             |
| Cube Sort        | O(n)          | O(n log n)       | O(n log n)         | O(n)             |

---

## 🛠️ How to Use

Each algorithm is implemented in its own Python file and documented with comments for clarity.

```bash
# Example
python quicksort.py

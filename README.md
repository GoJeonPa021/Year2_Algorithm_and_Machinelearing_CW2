# Year2_Algorithm_and_Machinelearing_CW2
# Algorithms and Machine Learning – Coursework 1 (MATH20017)

This repository contains my solutions for **Assessed Coursework 1** of the unit  
**Algorithms and Machine Learning (MATH20017)**, Autumn 2024.

The coursework covers fundamental algorithmic techniques including
divide-and-conquer analysis, randomized algorithms, sorting, inversion counting,
and deterministic selection.

---

## 📁 Contents

- `Coursework1.ipynb`  
  Jupyter notebook containing **all implementations, proofs, and tests**.

- `Coursework1.pdf`  
  Exported PDF version of the notebook, submitted for assessment.

---

## 🧠 Coursework Overview

### Question 1: Divide-and-Conquer Algorithms
- Proof that the **key lemma for the Master Method** implies the Master Method bound.
- Proof of the **key lemma** itself.
- All arguments are written clearly and follow the lecture proof strategy.

---

### Question 2: Monte Carlo Method
- Implementation of a **Monte Carlo estimator for π**.
- Uses i.i.d. uniform random variables and geometric probability.
- Achieves accuracy to **2 decimal places**, verified against `numpy.pi`.

---

### Question 3: Quick Sort Algorithm
- Implementation of **randomised Quick Sort** in Python.
- Correctness tested against Python’s built-in `sorted` function.
- Formal proof that the **expected runtime is O(n log n)**.

---

### Question 4: Counting Array Inversions
- Efficient **divide-and-conquer algorithm** for counting inversions.
- Runs in **O(n log n)** time.
- Includes:
  - `count_inv_and_sort`
  - `count_split_inv_and_merge`
- Verified against a naive Θ(n²) inversion counter.

---

### Question 5: Selection Problem
- Deterministic linear-time selection algorithm (**Median of Medians**).
- Python implementation of `deterministic_select`.
- Correctness verified using extensive randomized testing.

---

## 🧪 Testing and Validation

All algorithmic implementations are tested using:
- Randomised input arrays
- Comparison against known-correct baseline methods
- Fixed random seeds for reproducibility

All tests pass successfully.

---

## ▶️ How to Run

1. Open the notebook:
   ```bash
   jupyter notebook Coursework1.ipynb

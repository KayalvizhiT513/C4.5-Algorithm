# 🌳 C4.5 Algorithm – Python Implementation

This repository contains a set of **Jupyter Notebooks** that implement and demonstrate the **C4.5 Decision Tree Algorithm**.  

The C4.5 algorithm is an extension of the ID3 algorithm and is widely used for classification tasks in machine learning. It improves upon ID3 by introducing support for **continuous attributes**, **handling of missing values**, and **tree pruning** for better generalization.

---

## 📖 What You’ll Learn

By exploring these notebooks, you will understand:

- How C4.5 builds decision trees from training data.  
- How **continuous attributes** are handled using threshold-based splitting.  
- How the algorithm deals with **unknown or missing values**.  
- How **pruning** reduces overfitting and improves prediction accuracy.  
- How to visualize decision trees using **Graphviz**.

---

## 📂 Notebooks Overview

- **`C4_5_algorithm_handles_continuous_attribute_.ipynb`**  
  Demonstrates how C4.5 determines split points and handles **continuous (numeric) attributes**.  

- **`C4_5_handles_unknowns.ipynb`**  
  Explains how the algorithm manages **missing or unknown attribute values** during tree construction.  

- **`C4_5_handling_unknowns_in_training_and_testing_data.ipynb`**  
  Extends the handling of unknowns to both **training and testing phases**, distributing fractional weights across branches.  

- **`C4_5_tree_pruning.ipynb`**  
  Implements **tree pruning**, which simplifies the tree and helps avoid overfitting while maintaining predictive performance.  

---

## ⚙️ Requirements

Install the required libraries before running the notebooks:

```bash
pip install pandas numpy graphviz matplotlib openpyxl

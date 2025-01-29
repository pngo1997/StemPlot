# 📊 Stem-and-Leaf Plot Generator

## 📜 Overview
This project generates **Stem-and-Leaf Plots** from numerical data files.  
A **Stem-and-Leaf Plot** is a visual representation of numerical data, similar to a histogram, but it **preserves individual data points**.

## 🎯 Features
- **Interactive Selection**: Users can choose from multiple datasets.
- **Automated Sorting**: Leaf values are sorted within each stem.
- **Continuous Mode**: The program loops until the user chooses to exit.

## 🛠 How It Works
1. The program **greets the user**.
2. It prompts the user to choose from **three available datasets** (`StemAndLeaf_1.txt`, `StemAndLeaf_2.txt`, `StemAndLeaf_3.txt`).
3. Based on the selection:
   - Reads the appropriate dataset.
   - Computes **stem** (leading digits) and **leaf** (last digit).
   - Displays a sorted **stem-and-leaf plot**.
4. The loop continues until the user **chooses to exit**.

## 📊 Example Output
```shell
Enter a file number (1, 2, or 3): 1
✅ Successfully loaded dataset.

Stem | Leaves
---------------
  1  | 2 4 5 8
  2  | 1 3 6 7
  3  | 0 2 5 9
---------------
Would you like to try another file? (yes/no): no

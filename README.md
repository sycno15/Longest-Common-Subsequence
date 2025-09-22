# Longest Common Subsequence (LCS)

This repository contains a Python implementation of the **Longest Common Subsequence (LCS)** problem using **Dynamic Programming**.  
The program prints the **DP matrix with directions (U/L/H)**, the **length of the LCS**, and the **LCS string**.

---

## 🔹 Features
- Builds the DP matrix for LCS calculation.  
- Prints **directions** for each step:
  - **U** → Up  
  - **L** → Left  
  - **H** → Diagonal / Match  
- Displays the **length of the LCS**.  
- Recovers and prints the **LCS string**.  

---

## 🔹 Example Output
Matrix with directions:
0H 0H 0H 0H
0H 1H 1L 1L
0H 1U 2H 2L
0H 1U 2U 3H

Length of LCS: 3
LCS: "ABC"

yaml
Copy code

---

## 🔹 Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Longest-Common-Subsequence.git
   cd Longest-Common-Subsequence
Run the Python file:

bash
Copy code
python lcs.py
Enter the two strings when prompted, and the program will display the DP matrix, directions, and LCS result.

🔹 Applications
Text comparison tools

DNA/protein sequence alignment

Version control (diff/merge tools)

Similarity detection in strings

🔹 License
This project is licensed under the MIT License – you are free to use, modify, and distribute it.

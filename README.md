# Programming for AI – Lab Assignment 1

This repository contains my solutions to **Lab Assignment 1** of the *Programming for AI* course. All five programs are written in Python and live in a single Jupyter Notebook (`p4ai__lab_assignment_1.ipynb`). They cover core Python fundamentals: lists, dictionaries, functions, loops, conditionals, string handling and file handling.

## Contents

| # | Program | Concepts used |
|---|---------|---------------|
| 1 | Student Result System | Lists, nested dictionaries, functions, grading logic, file handling |
| 2 | Sentence Analyzer | Strings, loops, lists, sorting, file handling |
| 3 | Product Billing System | Dictionaries, functions, discount logic, file handling |
| 4 | Menu-Driven Calculator | `while` loop, `if/elif`, arithmetic operators |
| 5 | Restaurant Ordering System | `while` loop, `if/elif`, running total, file handling |

---

## Question 1 – Student Result System

Takes details of **5 students** (name, roll number, marks in Python, AI and Mathematics) and stores each student as a dictionary.

For each student the program:
- Calculates **total marks** (out of 300) and **percentage**
- Assigns a **grade**:

  | Percentage | Grade |
  |-----------|-------|
  | 80 – 100  | A |
  | 70 – 79   | B |
  | 60 – 69   | C |
  | 50 – 59   | D |
  | Below 50  | F |

- Saves the result (name, total, percentage, grade) to `result.txt`

Finally, it displays the **student with the highest percentage**.

## Question 2 – Sentence Analyzer

Reads a sentence from the user and reports:
- Total number of words
- Total number of characters
- Longest word and shortest word
- Total number of vowels
- List of unique words
- Words sorted in alphabetical order

All results are appended to `analysis.txt`.

## Question 3 – Product Billing System

Takes details of **5 products** (name, price, quantity) and:
- Calculates the total price of each product (`price × quantity`)
- Calculates the overall bill
- Applies a **10% discount** if the bill is **10,000 or more**
- Shows the **most expensive product**
- Saves all product details and the final bill to `bill.txt`

## Question 4 – Menu-Driven Calculator

A simple calculator that keeps running until the user chooses to stop. After entering two numbers, the user picks an operation:

1. Addition
2. Subtraction
3. Multiplication
4. Division
5. Modulus

Entering `1` at the prompt continues the program; `0` exits.

## Question 5 – Restaurant Ordering System

A menu-based ordering program:

| Item | Price |
|------|-------|
| Burger | 500 |
| Pizza  | 800 |
| Fries  | 250 |
| Drink  | 150 |

The user can place multiple orders with quantities. When finished, the total bill is displayed and saved to `order.txt`.

---

## Requirements

- Python 3.x
- Jupyter Notebook / JupyterLab (or Google Colab)

No external libraries are needed.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   cd <your-repo-name>
   ```
2. Start Jupyter:
   ```bash
   jupyter notebook
   ```
3. Open `p4ai__lab_assignment_1.ipynb` and run each cell in order. Each cell is one question and will ask for input in the notebook.

## Output Files

Running the programs creates these text files in the same folder:

- `result.txt` – student results (Question 1)
- `analysis.txt` – sentence analysis (Question 2)
- `bill.txt` – product bill (Question 3)
- `order.txt` – restaurant bill (Question 5)

## Sample Output (Question 1)

```
name =  asma
total marks =  224
percentage =  74.66666666666667
grade =  B

 STUDENT WITH HIGHEST PERCENTAGE
Name = asma
Roll No = 2
Percentage = 74.66666666666667
Grade = B
```

## Author

**Aqsa Saleem**
Roll No: `F25-BSAI-0098`
Course: Programming for AI

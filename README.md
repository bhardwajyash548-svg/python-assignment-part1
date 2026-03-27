# python-assignment-part1

# 📊 Student Grade Tracker — Task 1

## 📌 Overview
This project is part of my Python assignment focusing on **data parsing and cleaning using basic Python concepts**.

In real-world applications, data is often messy (extra spaces, wrong formats, inconsistent casing).  
In this task, I cleaned and structured raw student data using Python.

---

## 📂 File Structure

python-assignment-part1/
├── part1_grade_tracker.py    (or .ipynb)
└── README.md

---

## 🎯 Objective

The goal of this task is to:

- Clean raw student data
- Convert data types properly
- Validate names
- Display structured output using formatted printing

---

## 🧾 Given Raw Data

- Names had extra spaces and inconsistent casing
- Roll numbers were stored as strings
- Marks were stored as a comma-separated string

---

## ⚙️ Steps Performed

### 1. Data Cleaning
- Used `.strip()` to remove extra spaces
- Used `.title()` to convert names into proper format

### 2. Data Type Conversion
- Converted roll number from string → integer using `int()`
- Converted marks string → list using `.split()` and `int()`

### 3. Name Validation
- Checked if each word in the name contains only alphabets using `.isalpha()`
- Printed:
  - ✓ Valid name
  - ✗ Invalid name

### 4. Formatted Output
- Displayed each student in a structured "profile card" using f-strings

### 5. Special Requirement
- Found student with roll number **103**
- Printed name in:
  - UPPERCASE
  - lowercase

---

## 🖥️ Sample Output

Student : Ayesha Sharma

Roll No : 101

Marks : [88, 72, 95, 60, 78]

---

## 💡 Key Concepts Used

- For loops
- String methods (`strip()`, `title()`, `split()`)
- Lists and dictionaries
- Type casting (`int()`)
- Conditional statements
- f-strings for formatting

  

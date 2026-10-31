# Student Performance Analytics System 

A Python-based data analysis project developed as part of the **Python with AI Internship** at **EWB Tech Academy**. This system automates the processing, evaluation, and performance analysis of student records using **Pandas** and **NumPy**.

---

## 🚀 Project Overview
The **Student Performance Analytics System** reads student records from a CSV dataset, calculates total and average marks, determines grades and pass/fail statuses, and performs statistical operations to generate a clean, comprehensive academic performance report.

---

## 🛠️ Technologies Used
* **Python** (Core logic and script execution)
* **Pandas** (Data loading, cleaning, and DataFrame manipulation)
* **NumPy** (Numerical calculations and statistical analysis)
* **Google Colab / VS Code** (Development environments)

---

## 📂 Dataset Structure (`students.csv`)
The project utilizes a dataset containing 12–15 student records with the following columns:
* `StudentID`: Unique identification number for each student
* `Name`: Full name of the student
* `Department`: Academic department/branch
* `Python`: Marks obtained in Python (out of 100)
* `SQL`: Marks obtained in SQL (out of 100)
* `HTML_CSS`: Marks obtained in HTML & CSS (out of 100)
* `Attendance`: Student attendance percentage

---

## ⚙️ Key Features & Implementation
1. **Data Loading & Inspection:** Uses Pandas to load `students.csv` and inspect dataset properties using `.info()`, `.head()`, and `.tail()`.
2. **Automated Calculations:** Computes **Total Marks** and **Average Marks** for individual students.
3. **Grading & Status Logic:** Automatically assigns grades (`A+`, `A`, `B`, `C`, etc.) based on average scores and determines **Pass/Fail** status.
4. **Statistical Analytics:** Computes class statistics including highest average, lowest average, total pass/fail counts, and subject-wise performance averages using NumPy/Pandas functions.
5. **Clean Reporting:** Displays a well-formatted summary table presenting the final academic report.

---

## 📦 How to Run the Project
1. Clone the repository or download the project files (`main.py` and `students.csv`).
2. Open the project in **VS Code** or upload it to **Google Colab**.
3. Ensure you have Pandas and NumPy installed in your environment:
   ```bash
   pip install pandas numpy

# Job-Sequencing-GUI-Python


# 📊 Job Sequencing GUI Tool (Oct–Nov 2024)

A user-friendly Python-based GUI tool for visualizing and comparing different **job scheduling rules** in industrial systems. Built using Tkinter, it generates random job data and allows users to apply six classic sequencing rules — with results saved directly to Excel.

---

## 📌 Project Info

- **Course:** Principles of Industrial Engineering  
- **Guide:** Prof. Bhupesh Kumar Lad  
- **Duration:** October 2024 – November 2024

---

## 💡 Features

- GUI built with **Tkinter**
- Supports 6 sequencing rules:
  - FCFS (First Come First Serve)
  - SPT (Shortest Processing Time)
  - LPT (Longest Processing Time)
  - Smallest Slack
  - Smallest Critical Ratio
  - Random Order
- Generates **random processing times and due dates** with adjustable ranges
- Exports results to **Excel (.xlsx)** using `openpyxl`

---

## 🖥️ Interface Preview

*(Add a screenshot of your GUI if available)*

---

## 🧠 How It Works

1. Enter the number of jobs.
2. Select:
   - Processing Time Case:
     - Case 1: 2–10 units
     - Case 2: 2–50 units
     - Case 3: 2–100 units
   - Due Date Case:
     - Case 1: 30%–90% of total processing time
     - Case 2: 50%–110% of total processing time
3. Choose a sequencing rule from the dropdown.
4. Click "Apply" to:
   - View results in the GUI
   - Export results to Excel

---

## 🧾 Sample Output

Results are saved in this format:

| Job | Processing Time | Due Date | Rule Used |
|-----|-----------------|----------|-----------|
| 1   | 14              | 65       | SPT       |
| 2   | 22              | 90       | SPT       |
| ... | ...             | ...      | ...       |

---




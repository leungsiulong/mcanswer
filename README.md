# Student Score Management System

A comprehensive, interactive Command-Line Interface (CLI) application built in Python. This system is designed for teachers and school administrators to manage, analyze, and visualize student academic scores locally without the need for a complex database.

# Key Features

The application is divided into a **Main Menu** for grade-wide operations and a **Class Management Menu** for specific classroom tasks.

### Main Menu Capabilities
* **Search Grade Subject Extremes:** Instantly find the highest and lowest scoring students in a specific grade (Forms 1-6) for a given subject.
* **Search Individual Student:** Look up a student's full academic profile (Name, Chinese, English, Maths scores) using their unique Student ID (e.g., `1A01`).
* **View Class/Grade Average Statistics:** Compare the average scores of all classes within a specific form against the overall grade average.
* **Generate Class Average Chart:** Generate and export a bar chart (`.png`) visualizing the average scores of all classes in a specific form for easy comparison.

### Class Management Menu (Per-Class Operations)
* **View Class Score Report:** Displays a cleanly formatted table showing all students in the class, their individual scores, average score, and calculated **Class Rank**.
* **CRUD Operations:** Easily **Add**, **Edit**, or **Delete** student records directly from the terminal. Changes are instantly saved to the CSV files.
* **Generate Individual Report Cards:** Automatically generate individual `.pdf` report cards for every student in the class. The report card calculates and displays both their **Class Rank** and their overall **Form Rank**.
* **View Pass Rate Statistics:** Calculates the pass rate (default pass mark: 50) for individual subjects (Chinese, English, Maths) and the percentage of students who passed all three subjects.

---

# Prerequisites & Installation

This application requires **Python 3.6 or higher**. It also relies on the `matplotlib` library to render the charts and generate the PDF report cards.

1. **Clone or download** this repository to your local machine.
2. **Install the required dependencies** using pip:

```bash
pip install matplotlib

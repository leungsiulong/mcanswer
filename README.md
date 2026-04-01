#  Student Score Management System

A comprehensive, command-line-based Python application designed to help teachers and administrators manage, analyze, and visualize student exam scores. 

This system reads and writes data using simple CSV files, making it easy to integrate with Excel. It also features automatic dependency management, so users don't need to manually install external libraries before running the program!

---

##  Features

* ** Auto-Dependency Installation:** Automatically detects and installs required third-party libraries (like `matplotlib`) if they are missing on the user's computer.
* ** Easy Data Storage (CSV):** Automatically reads from and writes to class-specific CSV files (e.g., `Data - 1A.csv`).
* ** Class Management (CRUD):** Easily View, Add, Edit, and Delete student records directly from the terminal.
* ** Data Visualization:** Generates and exports beautiful bar charts (`.png`) comparing class averages using Matplotlib.
* ** PDF Report Cards:** Automatically generates stylized, individual PDF report cards for an entire class in seconds.
* ** Statistical Analysis:** Calculate pass rates, find the highest/lowest scorers in a grade, and calculate class rankings automatically.
* ** Global Search:** Instantly look up any student's grades using their unique Student ID.

---

##  Getting Started

### Prerequisites
* **Python 3.6 or higher** installed on your computer.
* Active internet connection (only required for the first run if `matplotlib` needs to be auto-installed).

### Running the Program
1. Place the script (`record_v5_Eng.py`) in a dedicated folder.
2. Open your terminal or command prompt.
3. Navigate to the folder containing the script.
4. Run the script using Python:
   ```bash
   python record_v5_Eng.py

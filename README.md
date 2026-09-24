# Simple Data Filtering Project

A lightweight Python project that demonstrates how to create a structured collection of student records and filter them using custom conditions based on grades and departments. 

This project fulfills the core objectives of understanding structured data filtering using native Python data structures (lists of dictionaries) and conditional logic.

## Project Structure

* `data_filtering.ipynb` - Jupyter Notebook containing step-by-step implementation.
* `data_filtering.py` - Single-file Python script execution.
* `README.md` - Project documentation.

## Features

- **Structured In-Memory Dataset**: Uses a list of dictionaries to represent a database of student records containing names, ages, test marks, and departments.
- **Custom Filtering Rules**: Implements modular, reusable functions for custom data querying:
  - Filter students by minimum score benchmarks.
  - Filter students by specific academic departments (case-insensitive checking).
- **Clean Formatting**: Output results are clearly organized in terminal logs or notebook cells.

## Getting Started

### Prerequisites

To run this project, make sure you have the following installed:
- Python 3.x
- Visual Studio Code (VS Code)
- **Python** and **Jupyter** extensions for VS Code (if running the notebook version)

### Running the Project

#### Option 1: Using Jupyter Notebook (`.ipynb`)
1. Open your project folder in VS Code.
2. Open `data_filtering.ipynb`.
3. Select your local Python kernel.
4. Click **Run All** or execute each cell sequentially using `Shift + Enter`.

#### Option 2: Using Standard Python Script (`.py`)
1. Create a file named `data_filtering.py` and paste the script code inside.
2. Open your terminal in VS Code and run the script:
   ```bash
   python data_filtering.py
   ```

## Example Output

```text
--- Test 1: Students with Marks >= 80 ---
Name: Ayush | Marks: 85 | Dept: AI & ML
Name: Ananya | Marks: 92 | Dept: Computer Science
Name: Sneha | Marks: 90 | Dept: Information Technology

==================================================

--- Test 2: Students in AI & ML Department ---
Name: Ayush | Age: 20 | Dept: AI & ML
Name: Rahul | Age: 21 | Dept: AI & ML
```

## Conceptual Q&A

### What is data filtering?
Data filtering is the process of extracting or selecting a specific subset of data records from a larger dataset based on defined constraints or conditional criteria. By filtering out unneeded information, developers and data analysts can isolate critical trends, clean data, and prepare datasets for more granular evaluation or reporting pipelines.
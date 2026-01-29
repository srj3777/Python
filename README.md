# Student Marks Dataset – Pandas & NumPy Processing

This repository contains a sample dataset (`random_marks.csv`) with 20 rows of student names and marks in various programming subjects.  
Some values intentionally include **special characters** (e.g., `90#`, `8@2`, `*35`) to simulate real‑world dirty data and test data‑cleaning workflows.

The project includes:
- A CSV dataset with mixed clean and corrupted values
- A Jupyter Notebook demonstrating Pandas and NumPy operations
- Examples of data cleaning, transformation, analysis, and export

---

## 📁 Dataset Overview

**File:** `random_marks.csv`

### Columns:
- `Name`
- `Python`
- `JAVA`
- `NET`
- `C`
- `ANGULAR`

Each subject column contains:
- Numeric marks  
- Marks with special characters  
- Some malformed entries to test cleaning logic  

---

## 🛠 Requirements

Install dependencies:

```bash
pip install pandas numpy

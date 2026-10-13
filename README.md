# NumPy Data Filtering

> Use NumPy conditions to identify values that are above, below, or equal to a specified threshold.

### 📌 Description
This project demonstrates numerical filtering using NumPy Boolean indexing. It filters data based on different threshold conditions.

### 🎯 Objective
Practice Boolean indexing and numerical filtering.

### 🛠️ Tools Used
- Python
- NumPy
- Jupyter Notebook

### 📂 Datasets Used
- Student marks
- Sales values

### 💻 Code Example
```python
import numpy as np

# Student marks array
student_marks = np.array([45, 67, 82, 91, 35, 55, 78, 49, 88, 62])

# Filtering with different thresholds
above_50 = student_marks[student_marks > 50]  # ABOVE
below_50 = student_marks[student_marks < 50]  # BELOW
equal_50 = student_marks[student_marks == 50]  # EQUAL
between_60_80 = student_marks[(student_marks >= 60) & (student_marks <= 80)]

print("Above 50:", above_50)
print("Below 50:", below_50)

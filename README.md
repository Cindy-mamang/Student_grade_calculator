# Student_grade_calculator
# Student Grade Calculator

## Project Overview

This project is a simple **Student Grade Calculator** developed using Python in Jupyter Notebook.

The program allows the user to enter a student's name and marks for **Math, English, and Computer**. It then calculates the student's average, assigns a grade, and determines whether the student has passed or failed.

## Technologies Used

* Python
* Jupyter Notebook
* Pandas

## Features

The program performs the following tasks:

1. Accepts the student's name.
2. Accepts marks for:

   * Math
   * English
   * Computer
3. Calculates the student's average mark.
4. Assigns a grade based on the average.
5. Determines whether the student **PASSes** or **FAILs**.
6. Displays the student's result clearly.

## Grading System

The program uses the following grading system:

| Average Mark | Grade |
| ------------ | ----- |
| 70 and above | A     |
| 60 – 69      | B     |
| 50 – 59      | C     |
| 40 – 49      | D     |
| Below 40     | F     |

### Pass/Fail Criteria

* **50 and above:** PASS
* **Below 50:** FAIL

## How It Works

The user is first asked to enter the student's information:

```python
name = input("Enter student name: ")
math = float(input("Enter Math mark: "))
english = float(input("Enter English mark: "))
computer = float(input("Enter Computer mark: "))
```

The average is then calculated:

```python
average = (math + english + computer) / 3
```

The program uses conditional statements to determine the grade:

```python
if average >= 70:
    grade = "A"
elif average >= 60:
    grade = "B"
elif average >= 50:
    grade = "C"
elif average >= 40:
    grade = "D"
else:
    grade = "F"
```

Finally, the program determines whether the student passed or failed.

## Example

For a student named **Justin** with an average of **58.33**:

```text
--- STUDENT RESULT ---
Name: Justin
Average: 58.33
Grade: C
Result: PASS
```

## How to Run the Project

### 1. Open the Notebook

Open the `.ipynb` file using **Jupyter Notebook** or **JupyterLab**.

### 2. Run the cells

Run the cells from top to bottom.

### 3. Enter the student's information

When prompted, enter:

* Student name
* Math mark
* English mark
* Computer mark

The program will automatically calculate and display the result.

## Project Structure

```text
Student-Grade-Calculator/
│
├── Student_Grade_Calculator.ipynb
└── README.md
```

## Purpose

The purpose of this project is to practice basic Python programming concepts, including:

* User input
* Variables
* Mathematical calculations
* Conditional statements
* Basic data processing
* Displaying results

## Author

**Cindy Mamang Kanga**

# Grade Calculator

A simple Python program to calculate grades based on marks.  
This program demonstrates the use of **if-elif-else**, **logical operators**, **nested conditions**, and **input validation**.

---

## Features

- Takes marks input from the user.
- Determines grades using if-elif-else conditions.
- Handles invalid marks (marks < 0 or > 100).
- Uses logical operators (`and`, `or`) for special cases.
- Displays proper messages for each grade.
- Includes nested conditions for borderline grades (e.g., B+, C+).
- Refactored grading logic into a function for readability.
- Allows testing multiple inputs at once.

---

## Grade Rules

| Marks         | Grade | Message                |
|---------------|-------|------------------------|
| 90 - 100      | A+    | Excellent!             |
| 80 - 89       | A     | Very Good!             |
| 70 - 79       | B/B+  | Good / Almost A        |
| 60 - 69       | C/C+  | C / Almost B           |
| 50 - 59       | D     | Just passed            |
| Below 50      | F     | Failed                 |
| Invalid Input | -     | Enter 0-100            |

---

## How to Run

1. Make sure you have **Python installed** (Python 3 recommended).
2. Save the program as `grade_calculator.py`.
3. Open a terminal or command prompt in the folder containing the file.
4. Run the program:

```bash
python grade_calculator.py
How many marks do you want to enter? 3
Enter marks for input 1: 92
A+ Grade - Excellent!
Enter marks for input 2: 67
C+ Grade - Almost B
Enter marks for input 3: 45
F Grade - Failed
Notes

Input must be numeric. Letters or empty input will display an error message.

Marks must be between 0 and 100 to be valid.

The grading logic is inside the calculate_grade() function for easier maintenance.

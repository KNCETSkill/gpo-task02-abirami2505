# GPO_Task02 – Java Coding Assessment

## Problem Title
Attendance Status Evaluator

## Objective
Develop a Java program that determines a student’s attendance status based on the given attendance percentage.  
This task evaluates your understanding of conditional statements, input handling using `Scanner`, and strict output formatting.

---

## Input Specification
- A single Positive integer representing attendance percentage.

---

## Output Specification
- Print **exactly one word** based on the rules below:
  - `Poor`
  - `Satisfactory`
  - `Excellent`
- Do **not** print any additional text, prompts, or symbols.
- Output is **case-sensitive**.
- No extra spaces or blank lines.

---

## Decision Rules
- Attendance > 85 → `Excellent`
- Attendance between 60 and 85 (inclusive) → `Satisfactory`
- Attendance < 60 → `Poor`

---

## Sample Test Cases

| Input | Output |
|------|--------|
| 90 | Excellent |
| 75 | Satisfactory |
| 45 | Poor |
| 60 | Satisfactory |
| 85 | Satisfactory |

---

## Instructions to Students
- Do **not** change the class name: `AttendanceStatusEvaluator`
- Write your logic **only inside the given file**
- Use `Scanner` for input
- Print output using `System.out.print()` or `System.out.println()`
- Do **not** add extra print statements

---

## Repository Structure (Do Not Modify)

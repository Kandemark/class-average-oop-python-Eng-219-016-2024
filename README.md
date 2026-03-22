# Class Average Program – OOP in Python
**CIT 2228 Computer Programming II**  
BSc Electrical and Telecommunication Engineering

## Description
A Python program that uses Object-Oriented Programming (OOP) to calculate the average grade of students in a class.

Two classes are implemented:
- `Student` – stores a student's name and grades, and calculates their individual average
- `ClassAverage` – manages a list of students and computes the overall class average

## Flowchart
```mermaid
flowchart TD
    A([Start]) --> B[Create Student class\\nwith name & grades attributes]
    B --> C[Create ClassAverage class\\nInitialize empty students list]
    C --> D[/Input number of students n/]
    D --> E{More students\\nto enter?}
    E -- Yes --> F[/Input student name & grades/]
    F --> G[Create Student object\\nAdd to students list]
    G --> E
    E -- No --> H[Call calculate_average\\nSum all grades divided by count]
    H --> I[/Display each student average\\nand class average/]
    I --> J([End])
```e

## Sample Output
```
========== CLASS RESULTS ==========
Alice Wanjiku: Grades = [78.0, 85.0, 90.0, 72.0, 88.0], Average = 82.60
Brian Otieno: Grades = [65.0, 70.0, 80.0, 75.0, 68.0], Average = 71.60
Carol Muthoni: Grades = [92.0, 88.0, 95.0, 91.0, 87.0], Average = 90.60
David Kamau: Grades = [55.0, 60.0, 72.0, 58.0, 65.0], Average = 62.00
Esther Akinyi: Grades = [80.0, 76.0, 84.0, 79.0, 83.0], Average = 80.40
------------------------------------
Class Average: 77.44
====================================
```

## How to Run
1. Clone the repository
2. Open `class_average.py` in any Python environment or Google Colab
3. Run the file and follow the prompts

## Technologies
- Python 3
- OOP principles: Encapsulation, Classes, Objects, Methods

## Author
mark mbugu  
BSc Electrical and Telecommunication Engineering

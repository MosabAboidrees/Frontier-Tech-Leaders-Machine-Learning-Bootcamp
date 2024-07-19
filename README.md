# BMI Calculator and Health Assessment

## Objective
The objective of this assignment is to build a Python program that calculates the Body Mass Index (BMI) of a user and provides a health assessment based on their BMI value.

## Background Context
BMI is a measure used to determine whether a person has a healthy body weight for their height. It is calculated using the following formula:

\[ \text{BMI} = \frac{\text{weight in kilograms}}{\text{height in meters}^2} \]

The BMI categories are:
- **Underweight**: BMI is less than 18.5
- **Normal weight**: BMI is 18.5 to 24.9
- **Overweight**: BMI is 25 to 29.9
- **Obesity**: BMI is 30 or greater

## Tasks

### User Input
- Prompt the user to input their weight in kilograms (float).
- Prompt the user to input their height in meters (float).

### Calculate BMI
- Using the formula provided, calculate the BMI. Store it in a variable named `bmi`.

### Provide Health Assessment
- Using conditional statements (`if`, `elif`, and `else`), determine which BMI category the user falls into.
- Print out the user's BMI and the corresponding health assessment.

### Error Handling
- Ensure the user cannot enter a negative or zero value for height or weight. If they do, provide an error message and prompt them to enter the value again.

## How to Run the Program
1. Ensure you have Python installed on your system. This program is compatible with Python 3.x.
2. Save the script as `bmi_calculator.py`.

python3 bmi_calculator.py



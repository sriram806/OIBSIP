BMI Calculator:
This is a simple Python script where the user inputting their weight and height to calculates the Body Mass Index and places the later into the different health stage.
Description:
The BMI Calculator script makes it possible for the participants to enter their weight in kilograms and their height in meters to generate their BMI. It then categorizes the BMI into one of the following categories:It then categorizes the BMI into one of the following categories:
      Underweight: BMI < 18. 5
      Normal weight: 18. Their BMI must be in the range of 5 to less than 25.
      Overweight: In other words it is of range 25 kg/m2 to 30 kg/m2.
      Obesity: BMI ≥ 30
In the script, the input validation for positive numbers is implemented and appropriate prompts as well as error messages are given for the user.

Functions:
calculate_bmi(weight, height):
Calculates the BMI using the formula:Calculates the BMI using the formula:
𝐵𝑀𝐼= 𝑤𝑒𝑖𝑔ℎ𝑡/ℎ𝑒𝑖𝑔ℎ𝑡**2

categorize_bmi(bmi):
Classifies the calculated BMI into the different categories defined by standard health categories.
Main Function:

The main() function drives the BMI calculation process:The main() function drives the BMI calculation process:
Causes the program to remain interactive and take weight and height inputs until correct inputs are entered.
Uses the above functions to calculate the BMI and categorise it.

# BMI-calculator-python
A simple BMI calculator in python for beginners 
# BMI Calculator
print("Welcome to BMI Calculator!")

# Input weight and height
weight = float(input("Enter your weight in kg: "))
height = float(input("Enter your height in meters: "))

# BMI formula
bmi = weight / (height ** 2)

# Result
print(f"Your BMI is: {bmi:.2f}")

# Category
if bmi < 18.5:
    print("You are Underweight")
elif 18.5 <= bmi < 25:
    print("You have Normal weight")
elif 25 <= bmi < 30:
    print("You are Overweight")
else:
    print("You are Obese")

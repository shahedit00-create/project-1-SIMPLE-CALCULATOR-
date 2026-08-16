# project-1-SIMPLE-CALCULATOR-
 This notebook takes two numbers and performs addition, subtraction, multiplication, and division.**

print("===== SIMPLE CALCULATOR =====") 
# Take two numbers from the user 
number1 = float(input("Enter first number: ")) 
number2 = float(input("Enter second number (not zero): "))
# Perform calculations 
addition = number1 + number2 
subtraction = number1 - number2
multiplication = number1 * number2 
division = number1 / number2

# Display the results 
print("\n===== RESULTS =====") 
print("Addition:", addition) 
print("Subtraction:", subtraction)
print("Multiplication:", multiplication) 
print("Division:", division)

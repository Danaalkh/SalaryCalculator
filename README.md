# SalaryCalculator
This is a simple Java program that calculates the total salary based on the hourly rate and hours worked, including any overtime pay.

## How to Use
- Clone the Repository: git clone https://github.com/your-username/salary-calculator.git
- Compile the Code : javac SalaryCalculator.java
- Run the Program: java SalaryCalculator
- Follow the Prompts:
  Enter the hourly rate.
  Enter the hours worked.
- View the Result:
  The program will display the total salary based on the inputs provided.
  
## Code Overview
- The SalaryCalculator class contains the main method, which prompts the user to input the hourly rate and hours worked. It then calculates and prints the total salary using the calculateSalary method.
- The calculateSalary method takes the hourly rate and hours worked as parameters and calculates the total salary. Overtime pay is calculated at 1.5 times the hourly rate for hours worked beyond 40 hours per week.

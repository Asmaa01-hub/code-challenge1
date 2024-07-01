# week1-code challenge
Repository for Week 1 code challenge
// README.md content
const readmeContent = 

 PROGRAMING CHALLENGES  README

This repository contains solutions to several programming challenges focused on practical scenarios.

** Challenges Overview


## Challenge 1: Student Grade Generator

**Purpose:** This function generates a grade based on student marks input by the user.

**Usage:**
1. Run the function.
2. Input student marks when prompted.
3. The function will output the corresponding grade based on the following criteria:
   - A > 79
   - B - 60 to 79
   - C - 50 to 59
   - D - 40 to 49
   - E - less than 40

### Challenge 2: Speed Detector

**Purpose:** This program calculates demerit points based on the speed of a car.

**Usage:**
1. Run the program.
2. Input the speed of the car when prompted.
3. The program will print "Ok" if the speed is less than 70 km/h.
4. For speeds 70 km/h and above, it calculates demerit points as follows:
   - For every 5 km/h above 70 km/h, one demerit point is added.
   - If the total demerit points exceed 12, the program prints "License suspended."

#### Challenge 3: Net Salary Calculator

**Purpose:** This program calculates the net salary of an individual after deductions.

**Usage:**
1. Run the program.
2. Input the basic salary and benefits when prompted.
3. The program will calculate the following:
   - Gross salary (basic salary + benefits).
   - Payee (Tax) based on KRA tax rates.
   - NHIF Deductions based on NHIF rates.
   - NSSF Deductions based on NSSF rates.
   - Net salary (gross salary - deductions).

**Additional Information:**
- Use the KRA, NHIF, and NSSF rates provided in the [KRA website](https://www.aren.co.ke/payroll/taxrates.htm) for accurate calculations.

##### Sample Inputs/Outputs:

For each program, here are some sample inputs and expected outputs:

 Student Grade Generator:
- Input: 80
- Output: Grade: A

 Speed Detector:
- Input: 78
- Output: Points: 2

 Net Salary Calculator:
- Input: 
  - Basic Salary: 60000
  - Benefits: 10000
- Output:
  - Gross Salary: 70000
  - Payee (Tax): 8000
  - NHIF Deductions: 500
  - NSSF Deductions: 1200
  - Net Salary: 60000

###### Requirements:

- JavaScript environment (Node.js, browser console, etc.) to run the programs.
- Ensure inputs are within valid ranges as specified.

 LICENCE:

This repository is licensed under the MIT License. See the LICENSE file for more details.
`;

// Print the README content to console
console.log(readmeContent);
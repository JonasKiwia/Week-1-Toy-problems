# Vanilla JavaScript Challenges

This repository contains solutions to three JavaScript challenges. These problems focus on basic programming concepts such as input handling, conditional statements, and calculations. Each solution is written in **vanilla JavaScript** and can be executed in a browser console or a Node.js environment.

---

/challenges
│
├── challenge1.js    // Student Grade Generator
├── challenge2.js    // Speed Detector
├── challenge3.js    // Net Salary Calculator
└── README.md        // Documentation

## Challenges

### 1. Student Grade Generator

This program prompts the user to enter student marks (0–100) and outputs the corresponding grade based on the following scale:

| Marks Range | Grade |
|-------------|-------|
| Above 79    | A     |
| 60–79       | B     |
| 50–59       | C     |
| 40–49       | D     |
| Below 40    | E     |

#### Usage
1. Run the program.
2. Enter the student's marks when prompted.
3. View the grade in the console.

---

### 2. Speed Detector

This program evaluates a car’s speed and determines:
- If the speed is within the limit.
- The number of demerit points issued for speeding.
- If the driver’s license should be suspended.

#### Rules
- Speed <= 70: Output `"Ok"`.
- For every 5 km/s above 70, 1 demerit point is added.
- If the total points exceed 12, the driver’s license is suspended.

#### Usage
1. Run the program.
2. Enter the car’s speed when prompted.
3. View the results in the console.

---

### 3. Net Salary Calculator

This program calculates an individual's **net salary** based on:
- **Basic Salary** and **Benefits**.
- Deductions: PAYE (Tax), NHIF, and NSSF.

#### Outputs
- **Gross Salary** = Basic Salary + Benefits
- **PAYE (Tax)**: Based on KRA tax brackets.
- **NHIF**: Calculated using NHIF rates.
- **NSSF**: Fixed at 200.
- **Net Salary** = Gross Salary - (PAYE + NHIF + NSSF)

#### Usage
1. Run the program.
2. Enter the basic salary and benefits when prompted.
3. View the breakdown of the salary in the console.

---




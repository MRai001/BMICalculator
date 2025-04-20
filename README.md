# BMI Calculator

## Overview
This is a simple command-line BMI (Body Mass Index) calculator application written in Java. The application calculates a user's BMI based on their weight in pounds and height in meters, then provides a health category based on the BMI value.

## Features
- Weight conversion from pounds to kilograms
- BMI calculation using the standard formula: BMI = weight (kg) / height (m)²
- Health category classification:
  - Underweight (BMI < 18.5)
  - Healthy weight (BMI 18.5-24.9)
  - Overweight (BMI 25-29.9)
  - Obese (BMI ≥ 30)
- User-friendly command-line interface

## Requirements
- Java Development Kit (JDK) 8 or higher
- Java Runtime Environment (JRE)

## How to Use
1. Compile the Java file:
   ```
   javac day4/BMICalculator.java
   ```

2. Run the compiled program:
   ```
   java day4.BMICalculator
   ```

3. Follow the on-screen prompts:
   - Enter your weight in pounds
   - Enter your height in meters

4. The application will display:
   - Your calculated BMI
   - Your health category based on the BMI value

## Example
```
Enter your weight in Pounds: 
150
Enter your height in meters: 
1.75
Your BMI is: 14.858723999999999
You are Underweight
```

## Code Structure
The application consists of a single Java class `BMICalculator` in the `day4` package. It uses `Scanner` to get user input, performs the necessary calculations, and outputs the results along with a health category.

## Formula Used
- Pounds to Kilograms: weight(kg) = weight(lbs) × 0.453592
- BMI Calculation: BMI = weight(kg) / height(m)²

## License
[Your License Here] - Feel free to modify and distribute this code as needed.

## Notes
- This is a basic BMI calculator and should not replace professional medical advice.
- BMI is a screening tool but does not diagnose body fatness or health.

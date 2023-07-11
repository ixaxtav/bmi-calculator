# BMI Calculator

This is the code for a simple BMI (Body Mass Index) calculator using HTML and jQuery.

## Features

- Allows users to calculate their BMI using metric or imperial units
- Updates the result and color-codes it based on the BMI category
- Provides a visual effect on the calculator title

## Installation

To use this BMI calculator, simply copy the provided HTML code into your project. Make sure to include the jQuery library by adding the following script tag:

```html
<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
```

## Usage

The BMI calculator consists of two tabs: "Metric" and "Imperial". Users can switch between these tabs to enter their weight and height in the respective units.

### Metric Tab

In the "Metric" tab, users are required to enter their weight in kilograms (kg) and height in centimeters (cm). Upon clicking the "Calculate BMI" button, the BMI value will be displayed along with the corresponding BMI category color.

### Imperial Tab

In the "Imperial" tab, users are required to enter their weight in pounds (lb), height in feet (ft), and inches (in). The BMI calculation for imperial units uses the formula `(weight / (height * height)) * 703`. The result is displayed along with the corresponding BMI category color.

## Additional Information

The BMI categories are defined as follows:

- Underweight: BMI < 18.5
- Normal weight: 18.5 ≤ BMI ≤ 24.9
- Overweight: 25 ≤ BMI ≤ 29.9
- Obesity: BMI ≥ 30

The calculator updates the color of the result text based on the calculated BMI category.

For any unit-specific input errors or when no values are entered, the result section remains empty.

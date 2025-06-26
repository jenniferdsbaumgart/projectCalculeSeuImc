
# Calcule Seu IMC - IMC Calculator

This is a simple IMC (Body Mass Index) calculator project created using HTML, CSS, and JavaScript. It calculates the IMC based on a person's weight and height, and categorizes the result according to standard BMI ranges.
## Project Overview

The IMC Calculator allows users to input their weight and height, and then it calculates the IMC (Body Mass Index). The result is displayed along with a category that indicates whether the user is underweight, normal weight, overweight, or obese. This project is part of the JavaScript and TypeScript: From Basic to Advanced course.

## Features

- IMC Calculation: Users can input their weight (in kilograms) and height (in meters) to calculate their IMC.
- Result Display: The IMC result is displayed with a corresponding category (underweight, normal, overweight, obesity).
- Error Handling: If invalid input is provided (e.g., non-numeric values), an error message is shown.
## Tech Stack

**HTML**: For structuring the form and the content of the webpage.
**CSS**: For styling the webpage and the form.
**JavaScript**: To handle the calculation, validation, and display of the IMC and categories.
## Code Explanation

JavaScript Logic

Event Listener for Form Submission:

- When the form is submitted, it triggers the submit event.
- It retrieves the weight and height values, validates them, and calculates the IMC using the getImc() function.

IMC Calculation:

- The formula for IMC is:
    IMC = Peso / (Altura * Altura).

IMC Categories:

The getNivelImc() function categorizes the result:

    Abaixo do peso: IMC < 18.5
    Peso normal: 18.5 ≤ IMC < 24.9
    Sobrepeso: 25 ≤ IMC < 29.9
    Obesidade grau 1: 30 ≤ IMC < 34.9
    Obesidade grau 2: 35 ≤ IMC < 39.9
    Obesidade grau 3: IMC ≥ 40
## Structure

- index.html: Main HTML file containing the structure and form.
- style.css: Contains the styles for the page, including the layout and form.
- main.js: Contains the JavaScript code for handling the form submission, IMC calculation, and result display.

## License

This project is for educational purposes and is open to use or modify as needed.

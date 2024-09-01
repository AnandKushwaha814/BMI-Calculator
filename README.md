# BMI-Calculator

## Snapshot

![Screenshot 2024-09-01 135303](https://github.com/user-attachments/assets/24b10ac3-675d-4f40-b2dc-cbf10fb840dd)


## This JavaScript code is designed to calculate and display the Body Mass Index (BMI) based on user input from a form.

1. Form Selection: The code selects the form element on the webpage using document.querySelector("form").

2. Event Listener: An event listener is attached to the form to listen for the submit event. When the form is submitted, the event is prevented from refreshing the page using e.preventDefault().

3. Input Retrieval: The code retrieves the values entered in the form fields for height and weight using document.querySelector("#height").value and document.querySelector("#weight").value.

4. Input Validation: The code checks if the input values for height and weight are valid (i.e., not empty, greater than zero, and are numbers). If the input is invalid, an error message is displayed in the results element.

5. BMI Calculation: If the inputs are valid, the BMI is calculated using the formula: BMI = weight / (height * height / 10000). The result is rounded to two decimal places.

6. BMI Category Determination: Based on the calculated BMI, the code determines the BMI category:

* Less than 18.6: Underweight
* Between 18.6 and 24.9: Normal weight
* Between 24.9 and 29.9: Overweight
* Greater than 29.9: Obese
* Displaying Results: The BMI category and value are displayed in the results element with corresponding emojis.

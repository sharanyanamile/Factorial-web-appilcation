# Factorial-web-appilcation
Project Documentation: Factorial Calculator
________________________________________
1. Project Overview
The Factorial Calculator is a web application that allows users to calculate the factorial of a positive integer using two different methods: iterative and recursive. The application is built using HTML, CSS, and JavaScript.
________________________________________
2. File Structure
•	index.html: The main HTML file that contains the structure of the web application.
•	styles.css: The CSS file that styles the web application.
•	script.js: The JavaScript file that contains the logic for calculating the factorial.
________________________________________
3. File Descriptions
3.1 index.html
•	Purpose: This file serves as the user interface for the Factorial Calculator.
•	Key Elements:
•	A title ((<h1>)) for the application.
•	An input field (<input>) for users to enter a positive integer.
•	Two buttons to trigger the factorial calculation using either the iterative or recursive method.
•	A <div> to display the result of the calculation.
3.2 styles.css
•	Purpose: This file contains the styles for the web application to enhance its visual appearance.
•	Key Styles:
•	General body styles (font, background color).
•	Container styles for centering and styling the main content area.
•	Input and button styles for better user interaction.
•	Result display styles for emphasis.
3.3 script.js
•	Purpose: This file contains the JavaScript logic for calculating the factorial.
•	Key Functions:
•	calculateFactorial(method):
•	Retrieves the user input and validates it.
•	Calls either the factorialIterative or factorialRecursive function based on the selected method.
•	Displays the result in the designated <div>.
•	factorialIterative(n):
•	Calculates the factorial of n using an iterative approach.
•	factorialRecursive(n):
•	Calculates the factorial of n using a recursive approach.
________________________________________
4. Usage Instructions
1.	Open the index.html file in a web browser.
2.	Enter a positive integer in the input field.
3.	Click on either the "Iterative" or "Recursive" button to calculate the factorial.
4.	The result will be displayed below the buttons.
________________________________________
5. Example
•	Input: 5
•	Output:
•	If "Iterative" is clicked: Factorial of 5 (iterative) is: 120
•	If "Recursive" is clicked: Factorial of 5 (recursive) is: 120
•	
6. Error Handling
•	If the user enters a non-positive integer or a non-numeric value, an error message will be displayed:
•	"Please enter a valid positive integer."
________________________________________
7. Conclusion
The Factorial Calculator is a simple yet effective tool for demonstrating the concept of factorials and the difference between iterative and recursive programming techniques. The project can be further enhanced by adding features such as input validation, error handling, and additional mathematical functions.



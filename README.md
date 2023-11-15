# Project Calculator

**Project Introduction**
A calculator is a fundamental tool used in various fields of mathematics, science, engineering, and everyday life. The Simple Calculator project involves building a basic calculator application that allows users to perform simple arithmetic calculations. The calculator will have a user-friendly interface with buttons for digits (0-9), operators (+, -, *, /), and additional functionality like All Clear, equals, and Delete Fuction. Users can input mathematical expressions, and the calculator will display the result.

**Project overview**
Developing a calculator project can be an excellent way to learn programming, improve your problem-solving skills, and create a practical application that can be used by others. In this introduction, we'll provide an overview of what a calculator project entails and discuss the key components you should consider. When developing a calculator project, you will design and implement a user-friendly interface for users to input mathematical expressions and obtain accurate results.

**Key Features of a Calculator Project**
1. User Interface (UI) - Designed a user-friendly interface that allows users to input mathematical expressions and display the results.

2. Expression Parsing - To parse the mathematical expressions entered by the user. This involves breaking down the input into individual components, such as numbers, operators, and parentheses, and organizing them in a way that allows for accurate calculation.

3. Mathematical Operations: Implementing functions or methods for performing various mathematical operations, including addition, subtraction, multiplication, division,

4. User Preferences: Allow users to customize the calculator's appearance, decimal precision, and other settings to enhance their experience.

**Programming Languages and Tools**
The choice of programming language and development tools used for this project are HTML CSS, JavaScript (for web-based calculators),

**Here's a breakdown of how this code works**
1. It selects an HTML element with the id "inputBox" and stores it in the variable input. This element is likely an input field where the calculator's input and output will be displayed.

2. It selects all the buttons on the page and stores them in the buttons variable using document.querySelectorAll('button').

3. It initializes two variables: string, which will store the current input string, and arr, which is an array converted from the NodeList of buttons obtained in step 2.

4. It iterates through each button in the arr array and adds a click event listener to each button.

5. Inside the click event listener for each button, it checks the button's inner HTML to determine its action:
   
     1.If the button's inner HTML is '=' (i.e., the equal sign), it evaluates the current string as a JavaScript expression using eval() and updates the string variable and 
       the input field (input.value) with the result.
   
     2. If the button's inner HTML is 'AC' (clear), it clears the string variable and sets the input field's value to an empty string.
        
     3. If the button's inner HTML is 'DEL' (delete), it removes the last character from the string variable and updates the input field.
     
     4. For all other buttons, it appends the button's inner HTML to the string variable and updates the input field.

7. This code effectively creates a simple calculator functionality where users can input arithmetic expressions using the buttons and see the result in the input field when they press the '=' button.

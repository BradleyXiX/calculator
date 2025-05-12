JavaScript Calculator

Overview
This is a JavaScript calculator built with React for the FreeCodeCamp Front End Libraries Certification. It implements a fully functional calculator that adheres to formula logic (similar to most standard calculators) and meets all project requirements.

View the live demo here (https://bradleyxix.github.io/calculator/)
Features

Performs basic arithmetic operations: addition, subtraction, multiplication, and division
Handles decimal input with appropriate validation
Follows formula logic with proper operator precedence
Provides reasonably precise calculations (up to 15 decimal places)
Responsive design that works on various screen sizes
Keyboard support for improved accessibility

User Stories Fulfilled
This calculator meets all the required user stories from the FreeCodeCamp project specification:

✅ Contains clickable elements for all numbers, operators, equals, and clear functions
✅ Displays input and output values appropriately
✅ Prevents invalid inputs like multiple zeros at the beginning or multiple decimal points
✅ Handles consecutive operators according to specifications
✅ Supports decimal operations with sufficient precision
✅ Implements formula logic rather than immediate execution logic
✅ Clears all input and resets to initial state with the clear button

Technologies Used

React (Hooks for state management)
CSS Grid for layout
JavaScript (ES6+)

How It Works
The calculator implements formula logic, which means it follows the standard order of operations (multiplication/division before addition/subtraction). The main components include:

Display area: Shows the current input and the formula being built
Number buttons (0-9): For entering numeric values
Operator buttons (+, -, *, /): For performing arithmetic operations
Decimal button (.): For entering decimal values
Equals button (=): For calculating the result
Clear button (AC): For resetting the calculator

Special Behaviors

Leading zeros are not allowed (e.g., typing "00" will just display "0")
Only one decimal point is allowed per number
Consecutive operators follow the "last operator" rule, with a special exception for the minus sign when used as a negative indicator
After evaluation (pressing =), starting a new operation with another operator will use the previous result

Testing
This calculator has been tested against the FreeCodeCamp test suite.

License
This project is licensed under the MIT License - see the LICENSE file for details.
Acknowledgments


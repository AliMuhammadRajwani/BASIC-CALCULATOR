
**Basic Calculator Program Using C++**

**Description:**

This program implements a basic calculator using C++. It includes functionalities for addition, subtraction, multiplication, and division. Here's an overview:

**1. Including Libraries:**
The program utilizes the standard input-output stream library (<iostream>) to handle input and output operations using cin and cout.

**2. Display Menu Function:**
This function presents a menu to the user, showcasing available operations such as addition, subtraction, multiplication, division, and an option to exit.

**3. Main Function:**

**Variable Declarations:**
- `choice`: An integer storing the user's menu selection.
- `num1` and `num2`: Double precision floating-point variables to hold the operands for arithmetic operations.
- `result`: A double precision floating-point variable storing the result of the performed operation.

**Main Loop:**
The program operates within an infinite loop, facilitating continuous interaction with the user until they opt to exit.

**Menu Display and User Input:**
The display Menu function is invoked to exhibit the menu, and the user’s choice is obtained using cin.

**Exit Condition:**
If the user selects option 5, a farewell message is displayed, and the loop is terminated using the `break` statement, ending the program.

**Input Validation:**
To ensure the user's choice is valid, the program checks if it falls within the range of 1 to 5. If not, an error message is shown, prompting the user to input a valid choice.

**Reading Operands:**
For valid arithmetic operations, the user is prompted to input two numbers (operands) which are then stored in `num1` and `num2`.

**Switch Statement for Operations:**
A switch statement is employed to execute the corresponding arithmetic operation based on the user’s choice:
- Addition
- Subtraction
- Multiplication
- Division

**Result Display:**
Following the operation, the result is displayed to the user.

**Division by Zero Check:**
To prevent runtime errors, the program checks if `num2` is zero before performing the division operation, displaying an error message if necessary.

**Summary:**
This basic calculator program offers a user-friendly interface with menu-driven navigation. It supports fundamental arithmetic operations and incorporates error handling to enhance robustness.

OUTPUT:

![Screenshot (379)](https://github.com/AliMuhammadRajwani/Basic-Calculator/assets/164401989/e0fa5e36-eba7-46eb-b533-b791648ee7dd)






# CGPA-and-GPA-calculator

## overview
This C++ program serves as a GPA and CGPA calculator with a simple command-line interface.
Let's break down its components:

1. User Interface:
The program displays a menu with options to calculate GPA, CGPA, view the calculation method, or exit.
After selecting an option, the user is prompted to input necessary data.
At the end of each calculation, the result is displayed along with options to perform another calculation, return to the main menu, or exit the application.

2. Data Input and Storage:
For GPA calculation, the user inputs the credit hours and points for each subject, which are stored in arrays (credit and point).
For CGPA calculation, the user inputs the GPA for each semester, stored in the semrs array.

3. Calculation Logic:
The GPA is calculated by multiplying each subject's credit by its corresponding point, summing up these values, and then dividing by the total credits.
The CGPA is calculated by summing up all the semester GPAs and dividing by the total number of semesters.

4. Error Handling:
The program does not include robust error handling. It assumes valid inputs from the user.
If the user enters an invalid option in the menu, they are prompted to re-enter a valid choice.

## Overall Flow:
The program starts by displaying the menu.
Based on the user's selection, it prompts for necessary inputs or displays information about the calculation method.
After calculation, it displays the result and provides options for further actions.
The user can choose to perform another calculation, return to the main menu, or exit the application.

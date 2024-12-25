# Age Calculator

This project is a simple **Age Calculator** built using HTML, CSS, and JavaScript. It allows users to input their date of birth and calculates their age based on the current date. The project also includes input validation to ensure correct and meaningful user inputs.

## Features

- **User-Friendly Interface**: The design includes a gradient background, rounded input fields, and buttons with hover effects for an enhanced user experience.
- **Input Validation**:
  - Ensures the user selects a date of birth.
  - Prevents future dates from being entered.
- **Dynamic Age Calculation**: Calculates the age accurately by considering the year, month, and day.
- **Responsive Feedback**:
  - Displays error messages in red for invalid inputs.
  - Shows the calculated age in green for valid inputs.

## Technologies Used

- **HTML5**: Structure of the web page.
- **CSS3**: Styling for a visually appealing frontend.
- **JavaScript**: Logic for input validation and age calculation.

## How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/age-calculator.git
    ```

2. Navigate to the project directory:
    ```bash
    cd age-calculator
    ```

3. Open the `index.html` file in your web browser.

## Code Explanation

### Input Fields
The form includes:
- A date input field for the user to select their date of birth.
- A button to trigger the age calculation.

### JavaScript Logic
- Extracts the selected date of birth using `document.getElementById("DOB").value`.
- Validates the input to ensure a valid and non-future date.
- Calculates the age by comparing the current date and the date of birth.
- Updates the output dynamically.

### CSS Styling
- **Gradient Background**: A linear gradient creates a visually appealing background.
- **Form Styling**: Rounded corners, shadows, and centered alignment enhance readability and usability.
- **Button Effects**: Hover effects provide visual feedback.

## Validation Details

1. **Empty Input Check**:
    If no date is selected, the program shows an error message: "Please select your date of birth."

2. **Future Date Check**:
    If the selected date is in the future, the program shows an error message: "Date of birth cannot be in the future."

3. **Valid Date Calculation**:
    For valid inputs, the program calculates the age in years and displays it.

## Future Enhancements

- Add additional styling for mobile responsiveness.
- Include support for more languages.
- Add a feature to calculate the exact age in years, months, and days.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature-name
    ```
3. Commit your changes:
    ```bash
    git commit -m "Add feature name"
    ```
4. Push to the branch:
    ```bash
    git push origin feature-name
    ```
5. Open a Pull Request.



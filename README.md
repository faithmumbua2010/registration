# Assignment 1: Student Registration Form

## Project Description

This project is a simple student registration form built using HTML. It incorporates client-side validation using JavaScript to ensure that the data entered by the user meets specific criteria before it could theoretically be submitted.

The form collects the following student information:
* Name
* Email
* Password
* Confirm Password

## Features

* **HTML Form Structure:** A clean HTML structure for the registration fields.
* **JavaScript Validations:**
    * **Required Fields:** Ensures that Name, Email, Password, and Confirm Password fields are not left empty.
    * **Email Format Validation:** Checks if the entered email address follows a standard email format (e.g., `user@example.com`).
    * **Password Matching:** Verifies that the values entered in the Password and Confirm Password fields are identical.
    * **Password Complexity:** Enforces password requirements:
        * Minimum length of 8 characters.
        * Must contain at least one number (0-9).
        * Must contain at least one uppercase letter (A-Z).
* **User Feedback:** Provides clear error messages near the respective fields when validation fails.

## Technologies Used

* HTML5
* JavaScript (ES6+)
* CSS

# Sumerge-Automation-Task
Welcome to the Sumerge Automation Task repository! This project contains automated tests for the login functionality of the Swag Labs application.

## Table of Contents
- Usage
- Testing Instructions
- Dependencies

## Usage
1. Open your favorite IDE (e.g., IntelliJ IDEA).
2. Import the project as a Maven project.
3. Run the LoginTests class to execute the test suite.

## Testing Instructions
### 1. Check Username and Password Fields
- Verify that the username input field and password input field are displayed on the login screen.
### 2. Verify Valid Login
- Enter valid credentials (**Username:** standard_user, **Password:** secret_sauce).
- After successful login, ensure that the “Swag Labs” div is visible.
### 3. Verify Invalid Login
- Enter invalid credentials.
- Confirm that the error message div displays the correct message.
### 4. Verify Empty Credentials
- Attempt to log in without entering any credentials. (Once without the username field and once without password field)
- Validate that the appropriate error messages are displayed.

## Dependencies
- Selenium WebDriver
- TestNG
- WebDriver Manager

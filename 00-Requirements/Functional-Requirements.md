# Functional Requirements

## Application

Swag Labs - SauceDemo

## Module: Authentication

### REQ-AUTH-001 - Login with valid credentials
The system shall allow a registered and active user to log in using a valid username and password.

### REQ-AUTH-002 - Invalid username
The system shall reject authentication when an invalid username is provided.

### REQ-AUTH-003 - Invalid password
The system shall reject authentication when an invalid password is provided.

### REQ-AUTH-004 - Empty username
The system shall prevent authentication when the username field is empty.

### REQ-AUTH-005 - Empty password
The system shall prevent authentication when the password field is empty.

### REQ-AUTH-006 - Empty credentials
The system shall prevent authentication when both username and password fields are empty.

### REQ-AUTH-007 - Locked user
The system shall prevent a locked-out user from accessing the application.

### REQ-AUTH-008 - Error message
The system shall display an appropriate error message when authentication fails.

### REQ-AUTH-009 - Successful login
After successful authentication, the user shall be redirected to the product inventory page.

### REQ-AUTH-010 - Password protection
The password entered by the user shall not be displayed in plain text.

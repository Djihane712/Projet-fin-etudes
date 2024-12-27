## Authentication

This project includes an authentication system that allows users to log in and access protected resources. The authentication process consists of the following steps:

1. **Login Page**: Users enter their credentials (username and password) on the login page (`login.html`).
2. **Server-side Validation**: Upon submission, the credentials are validated on the server using Python (`homepage.py`).
3. **Successful Login**: If the credentials are correct, users are redirected to the main page or their dashboard.
4. **Error Handling**: If the credentials are invalid, an error message is displayed, and the user is prompted to try again.

### Files involved:
- `login.html`: The HTML form for user login.
- `style.css`: The styling for the login page and other UI elements.
- `homepage.py`: The Python script that handles authentication on the server side.

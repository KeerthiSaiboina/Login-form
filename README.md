# Login-form
### State Management:
The component manages email, password, and error states using the useState hook.
### Form Submission:
The handleSubmit function is called on form submission.
It sends a POST request to /api/users/login with the email and password in the body.
### Token Handling:
If the login is successful, the JWT token received from the backend is stored in localStorage.
After login, the user is redirected to /tasks using the useNavigate hook.
### Error Handling:
If an error occurs (e.g., invalid credentials), it displays an error message.

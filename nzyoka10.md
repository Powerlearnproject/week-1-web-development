## Expense Tracker App - Basic HTML Template
- This document describes the basic HTML template for the Expense Tracker App interface.

### Template Breakdown
- The template includes the following elements:
    - **Document Declaration**: ``DOCTYPE html``
    - **HTML Root:** ``<html>`` element with language attribute (``lang="en"`` for English)
    - **Head Section:** ``<head>`` element containing meta information
        - **Character Encoding:** ``<meta charset="UTF-8">``
        - **Viewport Configuration:** ``<meta name="viewport" content="width=device-width, initial-scale=1.0">``
        - **Page Title:** ``<title>Expense Tracker App</title>``
    - **Body Section:** ``<body>`` element containing the visible webpage content.
        - **Header:** ``<header>`` section with application title (``<h1>Expense Tracker</h1>``) and description (``<p>Take control of your finances!</p>``)
        - **Registration Form:** ``<section>`` with registration form (``<h2>Register Now</h2>``)
            - User information fields with labels and input elements for name, email, and phone number.
            - Submit button (``<button type="submit">Register</button>``)
        - **User Information Table:** ``<table>`` element with user data columns (Name, Email, Phone Number)
            - `Empty table` body (``<tbody>``) for populating user information dynamically.
        - **Image:** ``<img>`` element referencing an image file ("image.jpg") with alternative text.
        - **External Link:** Paragraph (``<p>``) with an anchor tag (``<a>``) linking to Google (``"Visit Google"``).
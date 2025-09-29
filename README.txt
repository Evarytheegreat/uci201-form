# UCI 201 Assignment One — Registration Form

This package contains a single HTML file (`Act7-1.html`) that implements the registration form shown in the assignment instructions.

## How to Run
1. Download the zip and extract.
2. Open `Act7-1.html` in a modern web browser (Chrome, Edge, Firefox).
3. Fill in the fields and test the validation rules.

## Features
- **Full Name**: Required, must not be blank.
- **Password / Confirm**: Required, at least 6 characters, must match.
- **Email**: Required, must be a valid format.
- **Phone Number**: Required, allows international formats (e.g. +254712345678).
- **Zip Code**: Optional, basic alphanumeric and hyphen, 3–10 characters.
- **Card Type**: Dropdown selector.
- **Card Number**: Optional, checks format (13–19 digits) and Luhn algorithm validity.
- **Expiry Date**: Optional, format MM/YY, must be in the future.
- Inline error messages displayed under each field.
- Register and Clear Form buttons.

## Notes
- Validation is performed client-side (JavaScript + HTML5).
- No data is actually submitted to a server; submission shows an alert then resets form.
- Code is accessible with ARIA live regions for error messages.

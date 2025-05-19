# Automation Project

## Project Overview

This project automates the generation of insurance cards and their distribution via email. It enhances operational efficiency by programmatically creating insurance cards and securely sending them to recipients using SMTP protocol.

## Environment Configuration

### `.env` File Setup

To ensure secure handling of sensitive information, this project requires a `.env` file located in the root directory. This file should contain the necessary environment variables for email functionality.

### Required Environment Variables

- `SMTP_user`: The SMTP username used for authenticating the email service.
- `SMTP_pass`: The SMTP password corresponding to the username.

### Sample `.env` File

```env
SMTP_user=your_smtp_username
SMTP_pass=your_smtp_password
```
## Security Notice
- Do not commit the .env file to version control to prevent exposing sensitive credentials.

- Confirm that .env is listed in your .gitignore file to exclude it from Git tracking.

- Keep your SMTP credentials confidential and avoid sharing them publicly.
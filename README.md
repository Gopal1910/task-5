# Working Contact Form to Email Using JavaScript

A responsive contact form that validates user inputs and sends emails directly from the browser using JavaScript, SMTP.js.

## Features

- **Form Validation**: Real-time validation for all input fields including email format checking
- **Email Sending**: Sends form data via email using SMTP.js
- **User Feedback**: Success notifications using SweetAlert2
- **Responsive Design**: Modern, mobile-friendly design with neon green accents
- **Error Handling**: Visual error indicators for invalid inputs

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- [SMTP.js](https://smtpjs.com/) - For sending emails


## Setup Instructions

1. **Clone or Download** the project files:
   - `index.html`
   - `script.js`
   - `style.css`

2. **Configure Email Settings**:
   - Open `script.js`
   - Replace the `SecureToken` with your own SMTP.js secure token
   - Update the `To` and `From` email addresses as needed

3. **Open in Browser**:
   - Simply open `index.html` in any modern web browser
   - No server required - runs entirely in the browser

## Usage

1. Fill in all required fields:
   - Full Name
   - Email Address (must be valid format)
   - Phone Number
   - Subject
   - Message

2. Click "Send Message" button

3. If all fields are valid, the form will send an email and show a success notification

4. The form will reset after successful submission

## Form Fields

- **Full Name**: Required text field
- **Email Address**: Required, must match email format
- **Phone Number**: Required text field
- **Subject**: Required text field
- **Message**: Required textarea

## Styling

The form features:
- Dark background (#1f242d)
- Neon green accents (#0ef)
- Poppins font from Google Fonts
- Responsive layout
- Hover effects on submit button

## Browser Support

Works in all modern browsers that support ES6 JavaScript features.

## Security Note

For production use, consider implementing server-side email sending for better security and reliability. This implementation uses client-side email sending for demonstration purposes.

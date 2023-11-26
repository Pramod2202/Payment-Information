# Payment-Information
# Payment Form

This HTML document represents a simple payment form for collecting user information and payment details. Below is an explanation of the structure and functionality of the form.

HTML Structure

Head Section
- Charset and Viewport Meta Tags: Specifies the character set and viewport settings for better rendering on different devices.
- Title: Sets the title of the webpage to "Payment Form."

 Body Section
- Form: The main form where users will input their information. The `action` attribute is currently empty, indicating that the form data will be submitted to the same page (replace with the actual submission endpoint when ready).

 Header: 
  - H1 Heading: Displays "Payment Form" as the main heading.
  - Paragraph: Informs users that required fields are marked with *.

- Contact Information Section:
  - H2 Heading: Indicates the start of the contact information section.
  - First Name and Last Name Fields: Text inputs for the user's first and last names, both marked as required.
  - Gender Fieldset: Radio buttons for selecting gender, with options for Male, Female, and Prefer Not to Disclose.
  
- Address Section:
  - Address Fieldset: Legend indicates this is a required section.
  - Street Address Textarea: A larger text input for the user's street address.
  - City, State, Zip Fields: Text inputs for city, state, and a number input for ZIP code, all marked as required.

- Email Field: A text input for the user's email address, marked as required.

- Payment Information Section:
  - H2 Heading: Indicates the start of the payment information section.
  - Card Type Dropdown: A dropdown menu for selecting the card type, with options for Visa, Master Card, American Express, Discover, and Paypal. Marked as required.
  - Card Number Field: A number input for the user's card number, marked as required.
  - Card Expiration Date Field: A date input for the card expiration date, marked as required.
  - CVV Field: A password input for the Card Verification Value (CVV), marked as required.

- Submit Button: A submit button with the label "Pay Now" to submit the form.


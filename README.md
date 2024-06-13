# SignUp_Revamp-11,12

## Description
This project contains an HTML page for updating a user's password. It includes form validation to ensure that the passwords meet specific criteria and match each other before submission. The page is styled using Tailwind CSS and the Poppins font and utilizes Firebase for storing password updates.

## Features
- **Password Update Form**: Allows users to enter and confirm a new password.
- **Form Validation**: Checks if the new password contains only allowed characters (letters, numbers, and underscores) and matches the confirmation password.
- **Error Messages**: Displays error messages if the passwords do not meet the criteria or do not match.
- **Responsive Design**: Uses Tailwind CSS for styling and responsiveness.
- **Firebase Integration**: Saves the new password to Firebase Realtime Database.

## Technologies Used
- HTML
- JavaScript
- Tailwind CSS
- Google Fonts
- Firebase

## Usage
1. Open the `index.html` file in your web browser.
2. Enter a new password and confirm it.
3. If the passwords meet the criteria and match, the form will be submitted and the new password will be saved to Firebase. Otherwise, appropriate error messages will be displayed.
4. The form will reset upon successful submission.

## Code Structure
### HTML
- The form consists of two password input fields and a submit button.
- Error messages are displayed in paragraphs below each input field.

### JavaScript
- Event listeners are added to handle form validation and submission.
- The `validateForm` function checks if the new password meets the criteria and matches the confirmation password.
- The `savetodb` function saves the new password to Firebase.
- Error messages are cleared before new validation checks.
- The form is reset after successful submission.

### Tailwind CSS
- The layout and styling are handled using Tailwind CSS classes for a responsive and modern design.
- The Poppins font is loaded from Google Fonts for improved aesthetics.

## Firebase Setup
- Ensure you have a Firebase project set up.
- Use your Firebase project's configuration details in the script for initialization.
- Ensure you have the appropriate database rules set in Firebase to allow writing to the database.


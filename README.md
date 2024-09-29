# Job Application Form

This project is a **responsive job application form** built with HTML and CSS. The form includes various input fields, a CV upload section, and a submit button. It's styled with an external CSS file for a clean and modern look. The project is designed to work seamlessly across different screen sizes, ensuring a user-friendly experience on both desktop and mobile devices.

## Features

- **Responsive Design**: The form is designed to adapt to different screen sizes using CSS grid and media queries.
- **Form Validation (HTML5)**: Includes email validation, required fields, and a date picker for selecting the application date.
- **File Upload**: Users can upload their CV directly through the form.
- **Interactive Button**: The submit button has hover effects for improved user interaction.
- **Clean Layout**: The form layout is structured to maintain clarity and ease of use, with distinct sections for each input field.

## Folder Structure

```plaintext
project-folder/
│
├── index.html    # HTML structure of the Job Application form
├── style.css     # External CSS file for styling the form
└── README.md     # Detailed information about the project
```

## Requirements

To view and edit the project locally, you’ll need the following:

- A text editor such as Notepad, Visual Studio Code, Sublime Text, or any code editor of your choice.
- A modern web browser (Chrome, Firefox, Edge, Safari, etc.).

## How to Use

### 1. Folder Structure

Ensure that both the `index.html` and `style.css` files are in the same folder as shown above.

### 2. Running the Project

1. Open the `index.html` file in your web browser to view the job application form.
2. You can open it by:
   - **Double-clicking** on the `index.html` file, or
   - Right-clicking the file and selecting **Open With > Browser Name**.

### 3. Customizing the Form

You can modify the form by editing the `index.html` file to add or remove form fields. For changing the styles (like colors, font sizes, etc.), modify the `style.css` file.

## HTML File (index.html)

The HTML file contains the structure of the job application form. It includes:

- **Text Inputs**: For collecting the user's first name, last name, email, and city.
- **Dropdown Menu**: For selecting the job role (Frontend Developer, Backend Developer, etc.).
- **Textarea**: For the user’s address.
- **Date Picker**: To allow the user to select a date.
- **File Upload**: To upload a CV.
- **Submit Button**: A button that the user can click to apply.

## CSS File (style.css)

The CSS file provides the design and layout of the form. It includes:

- **Global Styles**: For resetting default margins and padding.
- **Container Layout**: A maximum width is set for the form, and it’s centered on the page.
- **Form Control Styling**: Styles for input fields, labels, and textareas, including padding, border-radius, and focus effects.
- **Responsive Design**: Media queries ensure that the layout adjusts on smaller screen sizes (e.g., mobile devices).
- **Button Styling**: The submit button changes color when hovered over, providing visual feedback to the user.

## Responsive Design

The CSS uses media queries to ensure that the form is responsive on smaller screens, such as smartphones. For example, if the screen width is below 460px, the textarea control spans a single column instead of two.

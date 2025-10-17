# Captcha Solver Application

This is a simple, single-file responsive HTML application designed to act as an interface for solving captchas. It uses Tailwind CSS for styling and vanilla JavaScript for dynamic behavior.

## Features

*   Displays a captcha image.
*   Allows users to input the text they see in the image.
*   Supports loading custom captcha images via a URL parameter.
*   Provides basic client-side validation for the default captcha.

## Usage

To use this application:

1.  Save the `index.html`, `README.md`, `LICENSE`, and `sample.png` files in the same directory.
2.  Open `index.html` in your web browser.

### Loading Custom Captcha Images

You can specify a custom image URL by appending a `?url=` parameter to the `index.html` file in your browser's address bar.

**Example:**
`index.html?url=https://example.com/path/to/your/image.png`

If no `url` parameter is provided, the application will default to displaying `sample.png`.

### Solving the Captcha

1.  Observe the text displayed in the captcha image.
2.  Type the text into the input field provided.
3.  Click the "Submit Captcha" button.

For the default `sample.png` image, the correct answer is `ADURZ`. A "Captcha Solved!" message will appear if you enter this correctly (case-insensitive). For other images, this client-side validation will not apply, and it's up to the user to determine correctness.

## Technologies Used

*   **HTML5**: Structure of the application.
*   **Tailwind CSS**: Utility-first CSS framework for responsive design and styling.
*   **JavaScript**: For dynamic image loading and client-side form handling.
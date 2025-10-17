# Captcha Solver Interface

This is a single-file responsive HTML application designed as a basic interface for solving image-based captchas. It uses Tailwind CSS for a clean and modern look.

## Features

*   **Responsive Design:** Adapts to various screen sizes using Tailwind CSS.
*   **Dynamic Image Loading:** Displays a captcha image. By default, it uses `sample.png`.
*   **URL Parameter Support:** You can specify an external image URL using the `?url=` query parameter (e.g., `index.html?url=https://example.com/some-captcha.png`).
*   **User Input Field:** Provides a text input for the user to enter their captcha solution.
*   **Submission Button:** A button to "submit" the entered solution (currently a mock submission for demonstration).

## Getting Started

1.  **Save the files:** Place `index.html`, `README.md`, and `sample.png` in the same directory.
2.  **Open `index.html`:** Open `index.html` in your web browser.

## Usage

*   **Default Mode:** The application will display `sample.png` as the captcha image.
*   **Custom Image:** To load a different image, append a `?url=` query parameter to the `index.html` URL in your browser.
    *   Example: `file:///path/to/your/folder/index.html?url=https://your-domain.com/path/to/your-captcha-image.png`
    *   *Note:* Ensure the image URL is accessible and does not violate any Cross-Origin Resource Sharing (CORS) policies if served from a different domain.

## Project Structure

*   `index.html`: The main single-file HTML application.
*   `sample.png`: The default captcha image.
*   `README.md`: This documentation file.
*   `LICENSE`: The MIT License for this project.

## Technologies Used

*   **HTML5:** Structure of the web page.
*   **Tailwind CSS:** For styling and responsive design.
*   **JavaScript:** For dynamic image loading and interactive elements.

## Disclaimer

This application provides an *interface* for captcha solving. The "solver" aspect is conceptual; it does not include actual backend logic or AI for automated captcha recognition. Users are expected to manually enter the solution.
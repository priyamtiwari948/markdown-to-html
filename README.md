# Markdown Viewer

This project provides a simple, single-file HTML application that converts Markdown content from an `input.md` file into HTML and renders it directly in the browser. It's built with responsiveness in mind, utilizing Tailwind CSS for styling and Marked.js for efficient Markdown parsing.

## Features

*   **Markdown to HTML Conversion:** Automatically fetches `input.md` and converts its content to renderable HTML.
*   **Responsive Design:** Styled with Tailwind CSS to ensure a consistent and appealing look across various devices and screen sizes.
*   **Lightweight:** A single HTML file that requires no complex build setup.

## Getting Started

To use this application, ensure you have the following files in the same directory:

*   `index.html`: The main application file.
*   `input.md`: Your Markdown content file.

Simply open `index.html` in your web browser. The application will automatically load `input.md` and display its rendered HTML version.

## Technologies Used

*   **HTML5:** The core structure of the web page.
*   **JavaScript:** Powers the fetching and parsing of Markdown content.
*   **Tailwind CSS (CDN):** A utility-first CSS framework for rapid and responsive UI development.
*   **Marked.js (CDN):** A fast and robust Markdown parser and compiler for JavaScript.

## File Structure

```
.
├── index.html
├── input.md
└── README.md
└── LICENSE
```

## License

This project is open-sourced under the MIT License. See the `LICENSE` file for more details.

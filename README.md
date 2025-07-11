# Modern API Client 🚀

A sleek, modern, and feature-rich API client built with HTML, Tailwind CSS, and vanilla JavaScript. This tool allows developers to quickly make HTTP requests, inspect responses, and manage a history of their API calls in a beautiful, responsive interface.

![API Client Screenshot](https://i.imgur.com/your-screenshot-url.png) 
*(Note: Replace with a URL to a screenshot of your application)*

## Features ✨

* **Full CRUD Support**: Make `GET`, `POST`, `PUT`, `PATCH`, and `DELETE` requests.
* **Custom Headers & Body**: Easily add custom headers and a raw JSON body to your requests.
* **Request History**: Automatically saves all requests to local storage for easy reuse.
* **cURL Import**: Quickly import requests by pasting a cURL command.
* **Webhook Simulation**: Set up repeating requests at a defined interval to test webhook endpoints.
* **Multiple Response Views**:
    * **JSON View**: A color-coded and syntax-highlighted view of the JSON response.
    * **Cards View**: Displays array items as individual, collapsible cards.
    * **Table View**: Renders JSON arrays in a structured table format.
* **Comprehensive Metrics**: Get detailed information about each response, including:
    * HTTP Status Code
    * Response Time
    * Content-Type & Content-Length
    * Rate Limiting Headers (`X-RateLimit-Limit`, `X-RateLimit-Remaining`, etc.)
    * Caching Headers (`Cache-Control`, `ETag`, `Last-Modified`)
    * And many more...
* **Modern UI/UX**:
    * Built with **Tailwind CSS** for a clean and utility-first design.
    * **Light & Dark Mode** support that respects system preferences.
    * Subtle animations with **GSAP** for a fluid user experience.
    * Fully responsive layout for use on any device.
* **Word Wrap Toggle**: Enable or disable word wrapping in the request body for better readability.

## Tech Stack 🛠️

* **Frontend**: HTML5, CSS3, JavaScript (ES6+)
* **Styling**: [Tailwind CSS](https://tailwindcss.com/)
* **Animations**: [GSAP (GreenSock Animation Platform)](https://greensock.com/gsap/)
* **Syntax Highlighting**: [Highlight.js](https://highlightjs.org/)
* **Icons**: Inline SVG (Heroicons)
* **Fonts**: [Google Fonts (Inter)](https://fonts.google.com/specimen/Inter)

## How to Use 📋

1.  **Clone the repository**:
    ```bash
    git clone [https://github.com/your-username/api-client.git](https://github.com/your-username/api-client.git)
    ```
2.  **Navigate to the project directory**:
    ```bash
    cd api-client
    ```
3.  **Open `index.html` in your browser**:
    * You can simply double-click the file or use a live server extension in your code editor (like Live Server for VS Code) for the best experience.

## Contributing 🤝

Contributions are welcome! If you have ideas for new features or improvements, feel free to open an issue or submit a pull request.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## License 📄

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

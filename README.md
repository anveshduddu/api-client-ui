# Modern API Client 🚀

Welcome to the Modern API Client, a sleek and powerful tool designed to make API testing and development a breeze. Built with a focus on simplicity, performance, and a great user experience, this client provides all the essential features you need in a beautiful, responsive interface. Whether you're debugging an endpoint, testing a new feature, or simply exploring an API, this tool is designed to be your perfect companion.

![API Client Screenshot](https://i.imgur.com/your-screenshot-url.png) 
*(Note: Replace with a URL to a screenshot of your application)*

## Features ✨

* **Full CRUD Support**: Effortlessly make `GET`, `POST`, `PUT`, `PATCH`, and `DELETE` requests to any endpoint.
* **Custom Headers & Body**: Easily add and manage custom HTTP headers and include a raw JSON body for your `POST`, `PUT`, and `PATCH` requests.
* **Persistent Request History**: Your entire request history is automatically saved to local storage, allowing you to quickly reload and re-run previous calls without manual setup.
* **Seamless cURL Import**: Save time by pasting a full cURL command directly into the client. It will automatically parse the method, URL, headers, and body.
* **Webhook Simulation**: Test your webhook integrations by setting up automated, repeating requests at a defined interval for up to two minutes.
* **Multiple Response Views**:
    * **JSON View**: A color-coded and syntax-highlighted view powered by Highlight.js makes reading complex JSON responses easy and intuitive.
    * **Cards View**: Automatically displays array items as individual, collapsible cards for better organization and readability.
    * **Table View**: Instantly renders JSON arrays in a structured, sortable table format, perfect for analyzing list-based responses.
* **Comprehensive Metrics**: Get detailed, at-a-glance information about each response, including status codes, response times, content types, rate limiting headers, caching policies, and much more.
* **Modern UI/UX**:
    * Built with **Tailwind CSS** for a clean, consistent, and utility-first design that is easy to maintain and customize.
    * **Light & Dark Mode** support that automatically adapts to your system preferences, ensuring comfortable viewing day or night.
    * Subtle, fluid animations powered by **GSAP** provide a smooth and engaging user experience without being distracting.
    * A fully **responsive layout** ensures the application is usable and looks great on all devices, from mobile phones to large desktop monitors.
* **Word Wrap Toggle**: Conveniently enable or disable word wrapping in the request body textarea to handle long lines of JSON or other text.

## Tech Stack 🛠️

This project leverages a modern, lightweight tech stack to ensure high performance and a great developer experience.

* **Frontend**: Built with standard **HTML5, CSS3, and JavaScript (ES6+)**, ensuring broad compatibility and a solid foundation without the overhead of a large framework.
* **Styling**: **[Tailwind CSS](https://tailwindcss.com/)** is used for its utility-first approach, which allows for rapid prototyping and building a highly customizable, responsive design system directly in the HTML.
* **Animations**: **[GSAP (GreenSock Animation Platform)](https://greensock.com/gsap/)** was chosen for its high-performance, professional-grade animation capabilities, adding smooth and fluid transitions to the UI.
* **Syntax Highlighting**: **[Highlight.js](https://highlightjs.org/)** provides fast, reliable, and themeable syntax highlighting for the JSON response viewer, greatly improving readability.
* **Icons**: **Inline SVG (Heroicons)** are used for their scalability, small file size, and ease of styling with CSS.
* **Fonts**: **[Google Fonts (Inter)](https://fonts.google.com/specimen/Inter)** was selected for its excellent readability and modern, clean aesthetic, which is perfect for user interfaces.

## How to Use 📋

Getting started with the API Client is simple. No complex build steps are required.

1.  **Clone the repository**:
    ```bash
    git clone [https://github.com/your-username/api-client.git](https://github.com/your-username/api-client.git)
    ```
2.  **Navigate to the project directory**:
    ```bash
    cd api-client
    ```
3.  **Open `index.html` in your browser**:
    * You can simply double-click the file to open it locally.
    * For the best experience, use a live server extension in your code editor (like **Live Server for VS Code**) to automatically reload the page on changes.

## Contributing 🤝

Contributions, issues, and feature requests are welcome! We believe in the power of community and are excited to see how you can help make this project even better.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

Please make sure to update tests as appropriate.

## License 📄

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

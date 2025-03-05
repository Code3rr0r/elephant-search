# Elephant Search Browser

A simple, privacy-focused browser built with Electron, featuring **Elephant Search** as the default search engine. This browser provides a minimalistic, user-friendly interface with fast search capabilities and the option to browse securely.

## Features

- **Search Integration**: Uses Elephant Search as the default search engine.
- **Minimal Interface**: A clean, distraction-free UI with a central search bar.
- **Cross-Platform**: Built using Electron, making it compatible with Windows, macOS, and Linux.
- **Customizable**: Future updates will allow customization of themes, extensions, and more.
- **Privacy-Focused**: Can be extended with privacy features such as incognito mode, ad-blocking, and more.

## Installation

### Prerequisites

Before running this app, ensure you have the following installed on your system:

- [Node.js](https://nodejs.org/) (Recommended version: 16 or higher)
- [npm](https://www.npmjs.com/)

### Steps to Run

1. **Clone the Repository**:

   If you haven't already, clone this repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/elephant-search-browser.git
   cd elephant-search-browser
   ```

2. **Install Dependencies**:

   Install the necessary dependencies via npm:

   ```bash
   npm install
   ```

3. **Run the App**:

   Launch the browser with Electron:

   ```bash
   npx electron .
   ```

   This will open the Elephant Search Browser on your default screen.

## Project Structure

Here is a brief overview of the project structure:

```
elephant-search-browser/
├── node_modules/         # Electron and other dependencies
├── package.json          # Project metadata and dependencies
├── main.js               # Main Electron app code (handles window and app lifecycle)
├── index.html            # Main HTML page (user interface with search bar)
├── style.css             # Styles for the browser UI
└── icon.png (optional)   # Custom browser icon (if you choose to add one)
```

### File Descriptions:

- **`main.js`**: This is the entry point of the Electron app. It creates the main window and loads the `index.html` file.
- **`index.html`**: The HTML file that contains the layout of the browser, including the search bar and webview.
- **`style.css`**: Basic styles for the search bar and the browser window.
- **`icon.png`**: Optional icon for your browser (you can replace it with your own design).

## Contributing

If you want to contribute to the project, feel free to fork the repository and submit pull requests. Here are some ways you can contribute:

- **Bug Fixes**: Report bugs or submit fixes.
- **Feature Requests**: Suggest new features or improvements.
- **Documentation**: Help improve the documentation and guide new users.

## License

This project is open source and available under the [MIT License](LICENSE).

---

### Acknowledgments

- [Electron](https://www.electronjs.org/) - Framework used to build the desktop app.
- [Google](https://www.google.com/) - The default search engine for this browser.

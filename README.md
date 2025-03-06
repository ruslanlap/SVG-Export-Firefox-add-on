# SVG Extractor Pro

![SVG Extractor Pro Header](data/header3.png)

<div align="center">
  <img src="icons/icon128.png" alt="SVG Extractor Pro Logo" width="128" height="128">
  
  <h3>Find, Extract, and Download SVG Images from Any Web Page</h3>

  [![Firefox Add-on](https://img.shields.io/badge/Firefox-Add--on-FF7139?style=for-the-badge&logo=firefox-browser&logoColor=white)](https://addons.mozilla.org/firefox/addon/svg-extractor-pro/)
  [![Version](https://img.shields.io/badge/Version-1.1.1-blue?style=for-the-badge)](https://github.com/yourusername/svg-extractor-pro/releases)
  [![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)
</div>

## 🚀 Features

- **Comprehensive SVG Detection**: Finds SVGs in various formats including inline SVGs, image tags, objects, embeds, and even CSS backgrounds
- **Modern User Interface**: Clean, responsive design with both light and dark mode support
- **Batch Download**: Download all SVGs at once as a ZIP file
- **Individual Downloads**: Download specific SVGs as needed
- **Preview Functionality**: View SVGs before downloading
- **Multilingual Support**: Available in English and Ukrainian
- **Copy SVG Code**: Copy SVG source code directly to clipboard

## 📸 Screenshots

<div align="center">
  <img src="data/header1.png" alt="SVG Extractor Pro Screenshot 1" width="400">
  <img src="data/header2.png" alt="SVG Extractor Pro Screenshot 2" width="400">
</div>

## 📋 How It Works

1. **Install the Add-on**: Add SVG Extractor Pro to your Firefox browser
2. **Navigate to Any Website**: Go to a website containing SVG images
3. **Click the Extension Icon**: The extension will scan the page for SVGs
4. **View Results**: Browse through all detected SVGs on the results page
5. **Download or Copy**: Save individual SVGs or download all as a ZIP file

## 🔧 Technical Details

SVG Extractor Pro uses advanced detection techniques to find SVG images that other tools might miss:

- Detects inline `<svg>` elements
- Finds SVG files loaded via `<img>` tags
- Discovers SVGs in `<object>` and `<embed>` elements
- Extracts SVGs used as CSS backgrounds
- Handles data URI SVGs

## 🛠️ Development

### Prerequisites

- Firefox Browser
- Node.js and npm (for development)

### Installation for Development

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/svg-extractor-pro.git
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Load the extension in Firefox:
   - Open Firefox
   - Navigate to `about:debugging`
   - Click "This Firefox"
   - Click "Load Temporary Add-on"
   - Select the `manifest.json` file from the project directory

## 🤝 Contributing

Contributions are welcome! Feel free to submit issues or pull requests.

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## ☕ Support

If you find this add-on useful, consider [buying me a coffee](https://ruslanlap.github.io/ruslanlap_buymeacoffe/).

## 📬 Feedback

Have suggestions or found a bug? [Leave feedback](https://forms.gle/xDCN4ACr5QKDmYkYA) or [report a bug](https://forms.gle/xDCN4ACr5QKDmYkYA).
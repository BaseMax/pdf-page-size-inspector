# PDF Page Size Inspector

A browser-based tool to upload a PDF and analyze the page dimensions in **pixels**, **millimeters**, and **centimeters**. It also detects whether pages are uniform in size and matches common paper standards such as **A3, A4, A5, Letter**, etc.

This project uses **HTML**, **CSS**, **JavaScript**, and **PDF.js** to run entirely in the browser with no backend required.

## Features

- Upload any PDF directly in the browser
- Detect page dimensions for every page
- Report sizes in:
  - **Pixels (px)**
  - **Millimeters (mm)**
  - **Centimeters (cm)**
- Identify if all pages have the same size
- Match pages to standard paper formats (A-series and others)
- Output results in a clean table view

## Live Demo

(You may include a GitHub Pages link here once deployed)

## Screenshot

*(Optional: add a screenshot of the UI here if available)*

## Getting Started

### Prerequisites

This tool runs entirely in the browser. There are no build tools or backend servers required. You only need:

- A modern web browser (Chrome, Firefox, Edge, Safari)
- The project files

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/BaseMax/pdf-page-size-inspector.git
````

2. Open `index.html` in your browser.

Alternatively, you can deploy it on **GitHub Pages** or any static hosting provider.

## Usage

1. Open the app in your browser.
2. Click **Choose File** and upload a PDF.
3. The page list and dimensions will be displayed automatically.
4. If all pages have the same size, a summary will indicate this.
5. If any page matches a standard paper size, its name (e.g., **A4**) will be displayed.

## Supported Paper Sizes

The application checks common standards including:

* A0, A1, A2, A3, A4, A5, A6
* Letter
* Legal
* Tabloid

## File Structure

```
pdf-page-size-inspector/
├── index.html        # Main HTML interface
├── style.css         # Visual styling
├── script.js         # Analysis and UI logic
├── pdf.min.js        # PDF.js library
└── pdf.worker.min.js # PDF.js worker
```

## Built With

* **HTML5** for structure
* **CSS3** for layout and design
* **JavaScript** for logic
* **PDF.js** (Mozilla) for PDF parsing and page metrics

## Contributing

Contributions are welcome! Typical ways to contribute include:

* Fixing bugs
* Improving UI/UX
* Adding export options (CSV/JSON)
* Adding additional paper formats

Steps to contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature-name`)
3. Make your changes
4. Submit a Pull Request

## License

This project is released under the **MIT License**.

Copyright 2025, Seyyed Ali Mohammadiyeh (Max Base)

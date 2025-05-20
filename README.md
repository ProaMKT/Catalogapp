# Catalog Web App

This project provides a simple web application for generating DIN A4 PDFs from user input. It uses Node.js, Express and Puppeteer to render HTML templates and return a PDF to the browser.

## Setup

1. Install dependencies (requires internet access):

```bash
npm install
```

2. Start the development server:

```bash
npm start
```

3. Open `http://localhost:3000` in your browser and fill in the form to generate a PDF.

## Notes

- Puppeteer runs a headless version of Chromium. The server is configured to run with the `--no-sandbox` flag for environments like containers.
- Generated PDFs will be sent directly to the browser as a download.

# PDF Splitter

A lightweight browser-based tool to extract a page range from any PDF file — no uploads, no servers, no internet required after the first load.

---

## Usage

1. Open `pdf-splitter.html` in Chrome, Firefox, or Edge
2. Drag and drop a PDF file onto the tool, or click to browse
3. Enter the start and end page numbers
4. Click **Cut & Download**
5. The extracted PDF downloads instantly to your machine

---

## Requirements

| | Details |
|---|---|
| Browser | Chrome / Firefox / Edge (2020 or later) |
| Internet | Required once to load the pdf-lib library; works offline after that |
| OS | Windows / macOS / Linux — anything with a modern browser |

> Internet Explorer is not supported.

---

## Privacy

Your file never leaves your device. All processing happens locally in the browser using [pdf-lib](https://github.com/Hopding/pdf-lib). Nothing is uploaded anywhere.

---

## Built With

- HTML / CSS / JavaScript — no frameworks
- [pdf-lib v1.17.1](https://github.com/Hopding/pdf-lib) — in-browser PDF read/write
- File API + Blob API — local file handling and download

---

## Features

- Extract any page range from a PDF
- Live preview showing page count and percentage of the file selected
- Auto-suggests an output filename
- Session history of completed operations
- Drag and drop support

---

## Files

```
pdf-splitter.html   — the entire tool, single file
README.md           — this file
```

---

## Author

Abdelrahman — Pentester & Cybersecurity Enthusiast

# BookPDFSlim 📖

**Smart in-browser scanned book PDF compressor.** Shrinks large books to exact target sizes (5MB, 8MB, 10MB) via 1-bit bilevel stencils and lossless MRC surgery with 100% searchable OCR text intact.

🔗 **Live Web App:** [https://madhuraj0.github.io/compress-book-pdf/](https://madhuraj0.github.io/compress-book-pdf/)

[![GitHub Stars](https://img.shields.io/github/stars/madhuraj0/compress-book-pdf?style=flat-square)](https://github.com/madhuraj0/compress-book-pdf)
[![License: MIT](https://img.shields.io/badge/License-MIT-amber.svg?style=flat-square)](LICENSE)
[![No Uploads](https://img.shields.io/badge/Privacy-100%25%20In--Browser-brightgreen.svg?style=flat-square)](https://madhuraj0.github.io/compress-book-pdf/)

---

### Features

- ⚡ **Multi-Engine Pipeline**: Auto-detects layered scan architectures (`/Mask` and `/SMask`), 1-bit bilevel text masks, and continuous-tone photographic plates.
- 🎯 **Target Size Mode**: Specify an exact target size (e.g. 5MB, 8MB, 10MB). Automatically budgets per-page resolution to guarantee meeting the byte limit.
- 🚀 **Max Shrink Mode**: Aggressive 1-bit bilevel quantization profile achieving 80%+ file size reductions for e-readers and mobile devices.
- 🔒 **100% Client-Side Privacy**: Runs entirely in your browser memory via JavaScript & WebAssembly. Documents never touch a server.
- 🛡️ **Integrity & OCR Verification**: Validates all pages, geometry, and vector OCR text streams (`BT ... ET`) post-compression.
- 🎨 **Reader Aesthetic**: Warm dark-mode palette designed for distraction-free reading environments.

---

### Topics & Tags

`pdf-compressor` • `scanned-pdf` • `mrc-compression` • `book-scanner` • `pdf-optimizer` • `ocr` • `jbig2` • `kindle` • `client-side` • `webassembly` • `pdf-lib` • `target-size`

---

### Local Run

No build step or server required. Simply clone and open:

```bash
git clone https://github.com/madhuraj0/compress-book-pdf.git
cd compress-book-pdf
open index.html
```

---

### License

MIT License. Free and open source.

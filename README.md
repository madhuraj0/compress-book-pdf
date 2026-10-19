# BookPDFSlim 📖

**Smart, multi-engine in-browser scanned book PDF compressor.**

Preserves OCR text, layout, and font sharpness while reducing file size by 30%–60%.

🔗 **Live Web App:** [https://madhuraj0.github.io/compress-book-pdf/](https://madhuraj0.github.io/compress-book-pdf/)

---

### Features

- ⚡ **Multi-Engine Pipeline**: Auto-detects layered scan architectures (`/Mask` and `/SMask`), bi-level text masks, and heavy photographic plates.
- 🎯 **Target Size Mode**: Specify a target size in megabytes (e.g. 10MB, 8MB). Automatically selects the optimal balance of lossless and progressive downsampling.
- 🔒 **100% Client-Side**: Runs entirely in your browser via JavaScript & WebAssembly. Documents never leave your computer.
- 🛡️ **Integrity Verification**: Built-in verification pass validates that all pages, layout geometry, and OCR text streams remain intact.
- 🎨 **Reader Aesthetic**: Minimalist, warm dark palette with zero clutter.

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

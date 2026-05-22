# PDF Compressor 📄⚡

A modern, privacy-first, client-side PDF compression tool. This application reduces PDF file sizes entirely within your web browser, ensuring your sensitive documents never leave your device.

## 🚀 Features

* **100% Private & Secure**: All processing happens locally on your machine. Zero server uploads.
* **Target File Size Compression**: Tell the app your desired maximum file size (e.g., 15MB for WhatsApp), and the smart compression logic will automatically adjust quality, DPI, and scaling to hit your target.
* **Intelligent Presets**:
  * **Recommended**: Balanced for email and general sharing.
  * **Maximum Compression**: Heavily optimizes images to achieve the smallest possible footprint.
  * **High Quality**: Preserves visual clarity while stripping unnecessary bloat.
* **Advanced Controls**: Fine-tune compression manually with options for image quality (slider), DPI resolution, grayscale conversion, JPEG vs. PNG encoding, and transparent background handling.
* **Modern UI/UX**: Features a premium drag-and-drop interface, real-time estimated output size calculation, dynamic processing state indicators, and a clean "Before & After" summary.

## 🛠️ Tech Stack

* **Frontend**: HTML5, Vanilla JavaScript, CSS (Tailwind CSS styling paradigm)
* **PDF Processing**: 
  * [PDF.js](https://mozilla.github.io/pdf.js/) (Mozilla) for rendering and parsing PDF pages.
  * [jsPDF](https://parall.ax/products/jspdf) for rebuilding the compressed document.

## 💻 How to Use

Since this is a fully client-side tool without any backend requirements, running it is incredibly simple:

1. Clone or download this repository.
2. Open the `pdf_size_reducer.html` file directly in any modern web browser (Chrome, Firefox, Safari, Edge).
3. Drag and drop your PDF into the upload zone.
4. Select your desired compression goal or dial in custom settings.
5. Click **Compress PDF** and wait for the local processing to finish.
6. Download your optimized file!

## 🔮 Roadmap / Future Enhancements

* **Batch Processing**: Compress multiple PDFs simultaneously.
* **Live Visual Preview**: Side-by-side comparison of text sharpness and image quality before downloading.
* **Smart Vector Preservation**: Heuristics to keep text as selectable vectors instead of rasterizing when possible.
* **Direct Sharing integrations**: Push directly to email clients or WhatsApp Web.

## 📜 License

MIT License

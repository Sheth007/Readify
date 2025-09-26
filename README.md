# Redify 📖

A simple, web-based file reader application that allows users to view and extract content from various document formats directly in their browser.

## 🚀 Features

- **Text File Reader** (.txt) - Upload and display plain text files
- **PDF Viewer** - View PDF documents with an embedded viewer
- **Word Document Reader** (.docx) - Extract and display content from Word documents
- **PowerPoint Reader** (.pptx) - Extract text content from PowerPoint presentations

## 📁 Project Structure

```
redify/
├── index.html                      # Main landing page with navigation
├── style.css                      # Global styling for all pages
├── To_Upload_txt.html             # Text file upload interface
├── To_Read_txt.html               # Text file display page
├── To_Upload_pdf.html             # PDF viewer interface
├── To_Upload_&_Read_docx.html     # Word document reader
└── To_Upload_ppt.html             # PowerPoint reader
```

## 🛠️ Technologies Used

- **HTML5** - Structure and file input handling
- **CSS3** - Modern styling with gradients and responsive design
- **JavaScript** - File processing and DOM manipulation
- **External Libraries:**
  - [Mammoth.js](https://github.com/mwilliamson/mammoth.js/) - For reading .docx files
  - [JSZip](https://stuk.github.io/jszip/) - For extracting content from .pptx files

## 🌐 Browser Compatibility
- Chrome (recommended)
- Firefox
- Safari
- Edge

*Note: Some features may require modern browser support for File API and HTML5.*

## ⚡ Key Features

- **No Server Required** - Runs entirely in the browser
- **Privacy First** - Files are processed locally, never uploaded to external servers
- **Clean UI** - Modern, intuitive interface with smooth animations
- **Fast Processing** - Quick file reading and display
- **Multiple Formats** - Support for the most common document types

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/improvement`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add some feature'`)
5. Push to the branch (`git push origin feature/improvement`)
6. Create a Pull Request

## 👥 Contributors

- **[Uday Sheth]** - Project Creator & Main Developer
- **[VishalBunny07]** - Contributing Developer

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- [Mammoth.js](https://github.com/mwilliamson/mammoth.js/) for Word document processing
- [JSZip](https://stuk.github.io/jszip/) for PowerPoint file handling
- All contributors who help improve this project

---

**Made with ❤️ for the developer community**

*If you find this project helpful, please consider giving it a ⭐ on GitHub!*

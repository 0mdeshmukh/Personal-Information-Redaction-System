# 🛡️ Personal Information Redaction System (GUI-Powered)

The **Personal Information Redaction System** is a user-friendly desktop application designed to automatically identify and redact sensitive personal information from various document formats. Leveraging **Microsoft's Presidio** for PII detection and **Tesseract OCR** for image processing, this tool ensures comprehensive redaction across PDFs, text files, and images. The intuitive GUI, built with **ttkbootstrap**, offers a seamless experience for users to secure their documents.

## 🚀 Key Features

- **Multi-format Support:** Redact PII from PDFs, text files (`.txt`, `.docx`), and images (`.png`, `.jpg`, `.jpeg`)
- **Advanced PII Detection:** Uses Microsoft's Presidio to detect entities like names, emails, phone numbers, dates, locations, and organizations
- **Image Redaction:** Integrates Tesseract OCR to identify and redact PII in image files
- **Modern GUI:** Designed with ttkbootstrap for a responsive, professional interface
- **Preview Functionality:** View documents before redaction
- **Threaded Processing:** Keeps the UI responsive during long tasks

## 🖥️ GUI Overview

- **Splash Screen:** A brief splash screen appears at startup
- **Home Screen:** Navigate between file types (PDF, Text, Image)
- **File Selection:** Choose a file from your system
- **Preview Area:** Displays document contents before redaction
- **Redaction Button:** Press "Secure It" to redact PII and save the result

## 📂 Supported File Types

- PDF Files: `.pdf`
- Text Files: `.txt`, `.docx`
- Image Files: `.png`, `.jpg`, `.jpeg`


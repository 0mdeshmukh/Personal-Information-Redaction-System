# 🛡️ Personal Information Redaction System 📄

The **Personal Information Redaction System** is a tool designed to automatically identify and redact sensitive personal information from PDF documents. It uses a combination of **Named Entity Recognition (NER)** through spaCy and **regular expressions** to detect and redact information such as:

⚖️ **Names**  
📧 **Emails**  
📞 **Phone numbers**  
📅 **Dates**  
🌍 **Locations** (GPE, LOC)  
🏢 **Organizations**, etc.

## How It Works 🔍

The system extracts text from PDF files, applies redaction using both **machine learning (NER)** and **regex** techniques, and generates a new PDF with all sensitive information replaced with `"[REDACTED]"`. This tool can handle both individual PDF files and folders containing multiple PDFs.

---

## Example 📑

**Input File:**  
Before redaction, the document contains sensitive information like email addresses, phone numbers, and personal names.

[**Supreme Court Judgement.pdf**](https://github.com/user-attachments/files/18218905/Supreme.Court.Judgement.pdf)

**Output File:**  
The redacted document with all sensitive information replaced with `[REDACTED]`.

[**Redacted Supreme Court Judgement.pdf**](https://github.com/user-attachments/files/18218922/Redacted_Supreme.Court.Judgement.pdf)

---

## Key Features ✨

- **Automatic Detection:** Uses spaCy's NER model to detect names, locations, and organizations.
- **Comprehensive Redaction:** Redacts emails, phone numbers, and dates using regex patterns.
- **User-Friendly:** Handles both single PDF files and entire folders of PDFs.
- **Secure:** Replaces sensitive information with `"[REDACTED]"` to protect privacy.

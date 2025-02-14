# 🛡️ Personal Information Redaction System (LLM-powered) 📄

The **Personal Information Redaction System** is a tool designed to automatically identify and redact sensitive personal information from PDF documents. It now leverages the power of **OpenAI's Language Model (LLM)** to identify and redact sensitive data with a high level of accuracy. This system is enhanced with **regular expressions** to ensure thorough redaction of information like:

⚖️ **Names**  
📧 **Emails**  
📞 **Phone numbers**  
📅 **Dates**  
🌍 **Locations**  
🏢 **Organizations**, etc.

## How It Works 🔍

The system extracts text from PDF files and uses **OpenAI's LLM API** in combination with **regex-based pattern matching** to redact personal information. The redacted information is replaced with `"[REDACTED]"`, and a new PDF is generated with the changes. The tool can process both single PDF files and folders containing multiple PDFs.

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

- **LLM-Powered Detection:** Uses OpenAI's Language Model to detect personal information like names, locations, and organizations with improved accuracy.
- **Comprehensive Redaction:** Redacts emails, phone numbers, and dates using regex patterns in addition to the LLM.
- **User-Friendly:** Handles both single PDF files and entire folders of PDFs, making it flexible for larger projects.
- **Secure and Robust:** Replaces all detected sensitive information with `"[REDACTED]"` to ensure privacy and security.

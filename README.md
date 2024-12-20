# Personal-Information-Redaction-System
The Personal Information Redaction System is a tool designed to automatically identify and redact sensitive personal information from PDF documents. It uses a combination of Named Entity Recognition (NER) through spaCy and regular expressions to detect and redact information such as:

Names,
Emails,
Phone numbers,
Dates,
Locations (GPE, LOC),
Organizations, etc

The system extracts text from PDF files, applies redaction using both machine learning (NER) and regex techniques, and generates a new PDF with all sensitive information replaced with "[REDACTED]". This tool can handle both individual PDF files and folders containing multiple PDFs.

# Pixtract – Image to Text OCR App with Dual Engine Support (Tesseract + EasyOCR)

Pixtract is a lightweight, powerful OCR (Optical Character Recognition) tool built with Python and Streamlit. Designed for educators, developers, researchers, and data entry operators, Pixtract converts images into editable text in seconds using both Tesseract and EasyOCR backends.

---

## Features

* **Dual OCR Support**: Choose between **Tesseract** or **EasyOCR**, or run both and compare results side-by-side.
* **Multi-language Text Extraction**: Supports multiple languages including English, Hindi, French, Arabic, and more via Tesseract.
* **Smart Image Preprocessing**: Improve accuracy with built-in resizing and contrast enhancement options.
* **Real-time OCR via Streamlit**: Upload your image and extract the text instantly via a clean web UI.
* **Easy Text Download**: Save the extracted text with a single click in `.txt` format.
* **Maintenance-aware UI**: Automatically detects Tesseract availability and gracefully switches to EasyOCR if needed.
* **Customizable Python Backend**: Modular, developer-friendly codebase to plug into larger applications.

---

## Getting Started

**Install the required packages**

```bash
pip install -r requirements.txt

streamlit run app.py

```

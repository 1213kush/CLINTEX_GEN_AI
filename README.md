# CLINTEX_GEN_AI
Medical Prescription Reading Using OCR and suggest Low cost generic  medicine 

# 🩺 Medical Prescription Reader using OCR

This project is designed to extract and digitize key information from medical prescriptions using **Optical Character Recognition (OCR)**. It enables automated reading of printed or handwritten prescriptions, converting them into structured digital data for easy access, editing, and further processing.

---

## 📌 Features

- ✅ Detects and reads printed or handwritten text from prescription images
- ✅ Extracts key medical fields like:
  - Patient Name
  - Doctor Name
  - Date
  - Medicine Names
  - Dosage & Frequency
- ✅ Outputs data in structured format (CSV/Excel)
- ✅ Reduces manual entry errors
- ✅ Can be extended for medicine recommendation, cost comparison, and digital record management

---

## 🧠 Technologies Used

- **Python 3.x**
- **Tesseract OCR** (via `pytesseract`)
- **OpenCV** – for image preprocessing
- **Pandas** – for tabular data structuring
- **Tkinter / Flask (Optional)** – for GUI or Web interface
- **Spacy / Regex** – for extracting and tagging medical entities

---

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:
- Python 3.x
- Tesseract OCR Engine  
  📌 [Install Instructions](https://github.com/tesseract-ocr/tesseract)

### Installation

```bash
git clone https://github.com/yourusername/medical-prescription-ocr.git
cd medical-prescription-ocr
pip install -r requirements.txt


🖼️ Input Format
Upload scanned or camera images of medical prescriptions (JPG, PNG, etc.)

Ensure image quality is clear (recommended: ≥ 300 DPI)




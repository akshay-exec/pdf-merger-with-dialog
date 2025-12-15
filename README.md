# PDF Merger with File Dialog (Python Automation)

## 📌 Overview
This Python script merges multiple PDF files from a specified folder into a single PDF file.  
It provides a **graphical “Save As” dialog** allowing users to choose the output file name and location interactively.

The PDFs are merged **in numeric order based on filename prefixes**, making it ideal for invoice and document sequencing.

---

## 🚀 Features
- Merges multiple PDF files into one
- Uses a graphical Save As dialog (Tkinter)
- Automatically sorts PDFs by numeric filename prefix
- Skips non-numeric or unrelated PDF files
- Simple, user-friendly execution

---

## 🛠️ Technologies Used
- Python
- PyPDF2
- Tkinter (GUI file dialog)

---

## ⚙️ Configuration
Update these paths inside the script before running:

```python
pdf_folder = r"PATH_TO_PDF_FOLDER"
```

---

## ▶️ How to Run

#### 1️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

#### 2️⃣ Run the Script
```bash
python merge_pdfs.py
```

---

## ⚠️ Requirements
- Python 3.8+
- Desktop environment (for Tkinter dialog)
- PDF filenames should start with a numeric prefix for correct ordering

---

## 📈 Use Case

#### Ideal for:
- Invoice merging
- Report compilation
- Document sequencing
- Logistics and finance operations

# 🚀 Resume Analyzer Based on Job Description

This project is an intelligent resume screening tool that analyzes resumes against a given job description and calculates the **ATS (Applicant Tracking System) Match Score**. It extracts relevant skills using OCR and NLP, suggests the best-fit roles, and visually represents the match with a pie chart.

## 📌 Features

- 📄 Upload resumes in **PDF format**
- 📝 Paste job descriptions directly into the interface
- 🔍 Extracts and matches **skills** using NLP + OCR
- 📊 Visualizes ATS match score with a **pie chart**
- 💼 Recommends the **best-fit roles**
- 🖥️ **Gradio-powered UI** for easy interaction

## 🛠 Tech Stack

- **Python**
- [Gradio](https://gradio.app/)
- [PyMuPDF (fitz)](https://pymupdf.readthedocs.io/en/latest/)
- [Tesseract OCR](https://github.com/tesseract-ocr/tesseract)
- [pdf2image](https://pypi.org/project/pdf2image/)
- [NLTK](https://www.nltk.org/)
- [Matplotlib](https://matplotlib.org/)

## 📥 Installation

```bash
pip install gradio pdf2image pytesseract nltk matplotlib PyMuPDF
sudo apt-get install -y poppler-utils
```

> ⚠️ Make sure [Tesseract OCR](https://github.com/tesseract-ocr/tesseract) is installed and added to your system path.

## 🧠 Roles Supported

This tool can evaluate resumes for roles like:

- AI/ML Intern
- Data Analyst
- Web Developer
- Backend Developer
- Cloud Engineer
- DevOps Engineer
- Cybersecurity Analyst
- Data Scientist
- Business Analyst
- Full Stack Developer

## ▶️ Usage

Run the Python file:

```bash
python resume_checker_18_(2).py
```

The Gradio interface will launch in your browser where you can:

1. Upload your **resume (PDF)**
2. Paste a **job description**
3. View your **ATS score**, **best fit role**, and **improvement tips**

## 📊 Output Example

- ✅ ATS Score Pie Chart
- 💡 Smart Recommendations
- 💼 Best Matching Role Based on Extracted Skills

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).


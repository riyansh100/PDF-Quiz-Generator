# 📘 PDF Quiz Generator (NLP + LLM)

A Streamlit-based web application that automatically generates Multiple Choice Questions (MCQs) from uploaded PDF or DOCX files using Google Gemini (Generative AI).
This tool is built for students, teachers, and anyone who wants to quickly convert study content into quizzes.

## 🚀 Features
- Upload PDF/DOCX files
- Auto-generate MCQs using Gemini
- Interactive quiz interface
- Automatic scoring
- Download MCQs as TXT or PDF

## 🧩 How It Works
1. Upload a PDF or DOCX
2. Text is extracted and sent to the LLM
3. MCQs are generated and displayed
4. User answers the quiz
5. Score is computed
6. Quiz can be downloaded

## 🛠️ Tech Stack
- Streamlit
- Google Gemini API
- pdfplumber
- python-docx
- FPDF
- Python

## ▶️ Running the App
```
pip install -r requirements.txt
streamlit run app.py
```

## 📄 License
MIT License

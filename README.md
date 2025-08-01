🩺 Med AI Analyzer

A smart AI-powered app that helps users understand their medical reports by:
- Extracting values from uploaded PDFs/images
- Showing clean visualizations (charts, trends)
- Using AI to explain terms in plain language
- Suggesting questions to ask your doctor

⚠️ This is not a diagnostic tool. Always consult a licensed healthcare provider.

## 🚀 Features
- PDF/Image parsing (OCR)
- GPT-4 / Gemini-based explanation
- Visual health summaries
- Privacy-first: no data stored

## 🛠 Tech Stack
- Python
- Streamlit
- OpenAI API / Gemini
- pdfplumber, pytesseract, Plotly

## 📂 Folder Overview
- `app/`: Core logic (parser, AI, charts, UI)
- `assets/`: Logos, sample reports
- `data/`: Reference medical ranges
- `notebooks/`: For testing/debugging

## ✅ How to Run
```bash
pip install -r requirements.txt
streamlit run streamlit_app.py

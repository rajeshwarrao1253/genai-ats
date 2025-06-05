# genai-ats

A modern Applicant Tracking System (ATS) web app built with Streamlit and Google Gemini (Generative AI). Effortlessly parse, analyze, and chat with resumes and job descriptions—just upload and get instant AI-powered insights.

## Features

- **Resume & JD Parsing:** Extract information from uploaded PDFs for automated screening.
- **AI-Powered Q&A:** Ask questions about resumes or job descriptions and get smart, context-aware answers.
- **PDF to Image Conversion:** Utilizes `pdf2image` for converting to image.
- **Conversational Memory:** Maintains chat history for a more interactive experience.
- **User-Friendly UI:** Simple, fast, and runs in your browser with Streamlit.

## Requirements

- Python 3.8+
- [Google Generative AI API Key](https://aistudio.google.com/app/apikey)
- See `requirements.txt` for all Python packages.

### Minimal requirements.txt

streamlit
google-generativeai
python-dotenv
pdf2image


Create a .env file in your project directory with:
GOOGLE_API_KEY=your-api-key-here


Mac/Linux only) Make sure Poppler is installed for PDF parsing:
brew install poppler

Run the app:
streamlit run app.py

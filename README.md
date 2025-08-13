# TalentScout Chatbot

An AI-powered recruitment assistant that generates 5 technical interview questions tailored to a candidate's tech stack.

## Features
- Candidate detail collection
- Automatic generation of exactly 5 technical questions using Google Gemini API
- Answer input fields
- Saves candidate details & answers to JSON
- Clean UI built with Streamlit

## Run Instructions
1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Create a `.env` file in the root directory with:
```
GEMINI_API_KEY=your_api_key_here
```

3. Run the app:
```bash
streamlit run app.py
```

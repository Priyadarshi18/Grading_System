# AI Grader – CBSE Economics

This Streamlit app allows teachers to upload a reference answer (PDF or image) and a student answer (image),
then uses Gemini + GPT-4o to extract and grade the student's response using CBSE-style evaluation.

## Run Locally
```
pip install -r requirements.txt
streamlit run app.py
```

## Features
- Upload reference answer (PDF/image)
- Upload handwritten student answer image
- Extract answers using Gemini OCR
- Grade answer using GPT-4o based on custom question and marks
- Instant CBSE-style feedback and grading

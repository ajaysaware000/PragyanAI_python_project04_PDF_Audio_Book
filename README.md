# PDF to Audio Book Converter

A Python-based web application that converts the text from a PDF file into an audio book using text-to-speech technology.

## Problem Statement

Reading long PDF documents can be time-consuming, especially for students, working professionals, and visually impaired users. Many people prefer listening to content while travelling or doing other work. Therefore, a simple application is needed that converts PDF text into audio format.

## Project Description

This project allows users to upload a PDF file and converts the text present in the PDF into speech. The application extracts text from the PDF using PyPDF2 and converts it into audio using gTTS (Google Text-to-Speech). The generated audio can be played directly in the web application.

The application was developed and tested in Google Colab using Gradio. A Streamlit web application was created for the frontend and deployed using Streamlit Cloud.

## Features

- Upload PDF file
- Extract text from PDF
- Convert extracted text into speech
- Play the generated audio book
- Simple and user-friendly web interface

## Technologies Used

- Python
- PyPDF2
- gTTS (Google Text-to-Speech)
- Gradio
- Streamlit
- Google Colab
- GitHub
- Streamlit Cloud

## Workflow

1. User opens the PDF to Audio Book Converter application.
2. User uploads a PDF file.
3. The application extracts the text from the PDF.
4. The extracted text is converted into speech using gTTS.
5. The audio file is generated.
6. User can play the audio book directly in the application.

## How to Run

1. Clone this repository:
   ```bash
   git clone <your-repository-link>
   ```

2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```

## Output

- PDF file is uploaded successfully.
- Text is extracted from the PDF.
- Audio book is generated successfully.
- User can listen to the generated audio.

## Live Application

[https://pragyanaipythonproject04pdfaudiobook-fkxxks2vude9hmdgarmp7y.streamlit.app/]

## Future Scope

- Add option to select voice speed
- Add multiple language support
- Add option to download the audio file
- Support scanned PDFs using OCR
- Add chapter-wise audio conversion

## Developed By

[Ajay Saware]

# Nepali Audio to Text Converter

## Overview
This is a desktop application that converts Nepali audio files (MP3, WAV, M4A) to text. It allows you to transcribe audio and save the result as a Word or PDF file.

---

## Features
- **Transcribe Nepali Audio to Text**: Convert audio files into text.
- **Save Transcription**: Save the transcribed text as a Word (.docx) or PDF (.pdf).
- **Simple User Interface**: Easy to use with buttons for uploading and saving files.

---

## How to Use
1. **Install Dependencies**:
   ```bash
   pip install ttkbootstrap pydub SpeechRecognition python-docx reportlab

# Nepali Audio to Text Converter

## Overview
This is a desktop application that converts Nepali audio files (MP3, WAV, M4A) to text. It allows you to transcribe audio and save the result as a Word or PDF file.

---

## Features
- **Transcribe Nepali Audio to Text**: Convert audio files into text.
- **Save Transcription**: Save the transcribed text as a Word (.docx) or PDF (.pdf).
- **Simple User Interface**: Easy to use with buttons for uploading and saving files.

---

## How to Use
1. **Install Dependencies**:
   ```bash
   pip install ttkbootstrap pydub SpeechRecognition python-docx reportlab

2. **Run the Application:**:
   ```bash
   python main.py

3. **Transcribe Audio:**:
  - Click "📤 Upload Audio & Transcribe" to upload an audio file.
  - Wait for the transcription to complete.

4. **Save Transcription:**
   - Once transcribed, you can click "💾 Save as Word" or "📄 Save as PDF" to save the text.

## How to Convert to EXE (Windows)

1. **Install PyInstaller:**:
   ```bash
   pip install pyinstaller

2. **Convert the app to an EXE:**:
   ```bash
   pyinstaller --onefile --windowed main.py

3. **The EXE will be in the dist/ folder.**:

## Libraries Used
- **ttkbootstrap**: For UI components.

- **pydub**: For audio file processing.

- **SpeechRecognition**: For transcribing audio.

- **python-docx**: For saving to Word documents.

- **reportlab**: For saving to PDF.
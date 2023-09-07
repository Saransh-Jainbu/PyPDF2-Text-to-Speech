# PyPDF2-Text-to-Speech

**Description:**

The "PyPDF2-Text-to-Speech" repository is a Python project that provides a simple yet powerful way to convert text from PDF documents into speech. This project leverages the PyPDF2 library for PDF parsing and the pyttsx3 library for text-to-speech synthesis.

**Features:**

1. **Text-to-Speech Conversion:** This repository includes a Python script that allows you to convert text to speech using the `pyttsx3` library. You can provide any text, and it will be read aloud in the language of your choice (default is English).

2. **PDF Text Extraction:** In addition to converting general text, the project also includes a feature to extract text content from PDF files using PyPDF2. It reads the entire PDF document and converts the extracted text into speech.

3. **Customizable Parameters:** The text-to-speech conversion is customizable. You can adjust properties such as speech rate, volume, and voice language to tailor the output to your preferences.

**Usage:**

To use this repository, follow these steps:

1. Import the necessary libraries:

```python
import pyttsx3
from PyPDF2 import PdfReader
```

2. Utilize the `text_to_speech` function to convert any text to speech:

```python
text_to_speech(text, language='en')
```

3. To read the entire content of a PDF file and convert it to speech, use the `read_pdf` function:

```python
read_pdf(file_path)
```

4. Customize speech properties as needed by modifying the `pyttsx3` engine settings within the `text_to_speech` function.

**Example:**

```python
pdf_file_path = r'example.pdf'  # Replace 'example.pdf' with the path to your PDF file
read_pdf(pdf_file_path)
```

**Note:** Ensure that you have the necessary libraries (`pyttsx3` and `PyPDF2`) installed to use this repository effectively.

With this project, you can easily convert text or PDF content into speech, making it a useful tool for various applications, including accessibility, automated reading, and more.

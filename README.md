PDF Translator
This repository contains a Jupyter notebook (PDF_traductor.ipynb) designed to translate PDF files containing text in German into English. It also includes a sample PDF (example.pdf) to help you test and use the code easily.

Features
Automatically translates text from German-language PDFs to English.

Generates a new PDF with the translated text.

Includes a sample PDF for demonstration and testing purposes.

Files Included
PDF_traductor.ipynb: Jupyter notebook with the code to translate PDF files.

example.pdf: Example input PDF in German.

Download the Example PDF
You can download the example PDF here to use it as a test input for the notebook.

Simply click the link, or right-click and choose “Save link as…” if your browser does not start the download automatically.

Requirements
Python 3.x

Jupyter Notebook

The following libraries:

pdfplumber (for extracting text from PDFs)

googletrans or deep-translator (for translating text)

fpdf or similar (for creating the translated PDF)

You can install the necessary dependencies with:

bash
Copiar
Editar
pip install pdfplumber googletrans==4.0.0-rc1 fpdf
Note: If you use a different translation or PDF library, please adjust this section according to your implementation.

Usage
Download or clone this repository.

Open the PDF_traductor.ipynb notebook with Jupyter Notebook.

Download the example.pdf file if you do not have it already.

Follow the instructions in the notebook cells.
You can use the provided example.pdf or upload your own German PDF file.

The script will generate a new PDF with the translated English text.

Quick Example
Load the example.pdf file.

Run the notebook.

Obtain the translated PDF as output.

Notes
The quality of the translation depends on the service used (Google Translate, DeepL, etc.).

The formatting of the translated PDF may differ from the original, especially if the PDF contains images or complex layouts.

Author
Ag78910

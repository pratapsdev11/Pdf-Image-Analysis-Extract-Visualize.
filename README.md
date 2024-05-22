# PDF Layout Extraction and OCR

This project provides a comprehensive workflow for extracting and processing layout elements from PDF documents using a combination of PDF to image conversion, layout detection with Detectron2, and OCR with Tesseract.

## Features

- **PDF to Image Conversion**: Converts each page of a PDF document into JPEG images for further processing.
- **Layout Detection**: Utilizes the Detectron2 model trained on the PubLayNet dataset to detect and categorize layout elements such as text blocks, titles, figures, and tables.
- **OCR with Tesseract**: Extracts textual content from detected layout elements using Tesseract OCR.
- **Table Extraction**: Converts detected tables into structured DataFrames for easy analysis.
- **Visualization**: Displays the first page of the PDF and visualizes detected layout elements on a selected page.

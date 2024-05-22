# PDF Layout Extraction and OCR

This project provides a comprehensive workflow for extracting and processing layout elements from PDF documents using a combination of PDF to image conversion, layout detection with Detectron2, and OCR with Tesseract.

## Features

- **PDF to Image Conversion**: Converts each page of a PDF document into JPEG images for further processing.
- **Layout Detection**: Utilizes the Detectron2 model trained on the PubLayNet dataset to detect and categorize layout elements such as text blocks, titles, figures, and tables.
- **OCR with Tesseract**: Extracts textual content from detected layout elements using Tesseract OCR.
- **Table Extraction**: Converts detected tables into structured DataFrames for easy analysis.
- **Visualization**: Displays the first page of the PDF and visualizes detected layout elements on a selected page.

 ## Flow Diagram
 ![dP9FZzCm4CNl_XH3BzjAQ96Gk3I7NPG_Ar21QBTyW26UDXQE7Nack-stnx4RgO83i2TNRtvJl_VYUnOCCWrMlT5qC8xWiIxt7xy-x6ebHYn1MpNG1jyHit57QAn_wVguenHBEhRVH-jH9x0nbWgrBRrxfY194W-V1ZmIHxqoF5eyHonmd4QrKCeSODrugod0ZVRT3TGdmy9t6v2U7AoTtoW0W6qP28NWcYqKEM](https://github.com/pratapsdev11/Pdf-Image-Analysis-Extract-Visualize./assets/109823056/b2fcbd31-83aa-44cd-b156-8a4af9c6b6c8)

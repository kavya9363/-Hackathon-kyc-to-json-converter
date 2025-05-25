# Document OCR and Classification API

A FastAPI backend service that extracts text and key entities from document images (like PAN, Aadhaar, Driving License) using Tesseract OCR and spaCy, and automatically classifies the document type.

## Features

- Upload images of documents  
- Extract text using Tesseract OCR  
- Perform Named Entity Recognition (NER) with spaCy  
- Classify document type based on extracted text  
- CORS enabled for frontend integration  

## Tech Stack

- Python 3.8+  
- FastAPI  
- Tesseract OCR (pytesseract)  
- OpenCV & PIL for image processing  
- spaCy for NLP  

## Setup & Run

1. **Install Python 3.8+** if not installed already.

2. **Install required Python packages:**  
   ```bash
   pip install -r requirements.txt


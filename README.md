# OCR Text Detection & Comparison (Tesseract vs EasyOCR)

This project compares two Optical Character Recognition (OCR) methods **Tesseract** and **EasyOCR** to detect and extract text from images.  
It measures the performance of both models using **Jaccard Similarity** across a dataset.

---

## Features

- Extracts text from images using Tesseract and EasyOCR  
- Cleans and normalizes detected text  
- Compares the similarity between results using Jaccard index  
- Evaluates accuracy across all dataset images

---

# How It Works

1. Extract dataset (text.zip) from Google Drive.
2. For each image:
  > - Read ground truth (from filename)
  > - Run OCR using Tesseract and EasyOCR
  > - Compute Jaccard similarity
3. Average the similarity scores to compare overall accuracy.

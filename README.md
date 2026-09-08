# BillWise AI

BillWise AI is an OCR-based bill processing application that extracts item details from a bill image and calculates individual expenses for shared bills.

# Overview

BillWise AI allows users to upload a bill photograph, extract item names and prices using OCR, assign items to different people, and automatically calculate how much each person needs to pay.

# Features

- Upload bill images
- Extract text using OCR
- Identify item names and prices
- Edit extracted bill details
- Add multiple users
- Assign items to one or more people
- Automatically calculate individual expenses
- Export the final split as CSV

# Tech Stack

- Python
- Streamlit
- Tesseract OCR
- PyTesseract
- Pandas
- Pillow

# Application Flow

```text
Bill Image
    ↓
Image Processing
    ↓
OCR Text Extraction
    ↓
Item & Price Detection
    ↓
Item Assignment
    ↓
Expense Calculation
    ↓
Final Bill Split

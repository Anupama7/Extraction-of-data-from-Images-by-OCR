
# Using Tesseract OCR with Python
- Extraction of data from Noisy images.

 ## Installing the Tesseract + Python “bindings”
 - pip install pillow
 - pip install pytesseract

## Download and install Tesseract OCR from this link.
- "https://digi.bib.uni-mannheim.de/tesseract/tesseract-ocr-w64-setup-v4.1.0-bibtag19.exe" 
- After installing find the "Tesseract-OCR" folder, double Click on this folder and find the tesseract.exe.
- After finding the tesseract.exe, copy the file location.
-  Pass this location into your code like this
pytesseract.pytesseract.tesseract_cmd = r"C:\ProgramFiles\Tesseract-OCR\tesseract.exe"
Note: C:\Program Files\Tesseract-OCR\tesseract.exe == your copied location

# License
MIT License



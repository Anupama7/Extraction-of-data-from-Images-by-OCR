# Using Tesseract OCR with Python
- Extraction of data from Noisy images.
- Tesseract is an optical character recognition engine for various operating systems. It is free software, released under the Apache License, Version 2.0, and development has been sponsored by Google since 2006. In 2006, Tesseract was considered one of the most accurate open-source OCR engines then available.

 ## Installing the Tesseract + Python “bindings” for windows
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

Copyright (c) 2019 Anupama

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


Aim : To extract Details of the Voters from the Voter list pdf in Hindi and add it to a csv

Used Open CV for drawig contours around boxes and after extracting the boxes from contour drawn on image ran it on Pytesseract OCR

As expected due to Hindi text data extraction was Unsucessful so i had to use the Pytesseract trained on Devangri Text

The results where smooth on Devangri Data except at some places where due to data discripancy was seen due to mix of English numeric Data and Devangri Data but this
issue was resolved in post cleaning after extraction


To run this simply open the Notebook and install the requierments on Colab by executingthe cell

pdf2image-for pdf to image conversion
pytesseract and dependancy-for ocr
devangri trained Data-For devangri extraction
1.Install pillow, pytesseract and opencv
	$ pip install pillow
	$ pip install pytesseract
	$ pip install opencv-python

2.Install setup of tesseract and update its path in script
	Installation link: https://github.com/UB-Mannheim/tesseract/wiki
	pytesseract.pytesseract.tesseract_cmd = 'C:\\Program Files (x86)\\Tesseract-OCR\\tesseract.exe'

3.To Run pass image with -image and filename as command line parameter
	$python ocr.py --image images/example_01.png
	Output:
	Noisy image
	to test
	Tesseract OCR
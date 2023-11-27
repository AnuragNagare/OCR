OCR Application using Tesseract OCR
This application is designed to perform Optical Character Recognition (OCR) on images using the Tesseract OCR engine. It provides a graphical user interface (GUI) built with Tkinter, allowing users to select an image file for text extraction.

Features
Image selection: Users can browse and select image files (supported formats: jpg, png, jpeg, jfif).
Image preview: Displays a preview of the selected image in the application window.
Text extraction: Processes the selected image using Tesseract OCR to extract text content.
Text output: Shows the extracted text in a separate window and saves it as an editable (.txt) file in the current directory.

Prerequisites
Python 3.x
Tesseract OCR installed (Ensure Tesseract is correctly installed and accessible via the provided path in the code)

Installation
Clone or download the repository to your local machine.

Install the required libraries using pip:
pip install opencv-python pytesseract pillow
Make sure Tesseract OCR is installed and set up on your system. Update the tesseract_cmd variable in the code with the correct path if needed.

Usage
Run the OCR_GUI.py file.
The application window will open, displaying the "SCAN IT!" button.
Click on the "SCAN IT!" button to start the OCR application.
Click the "CHOOSE" button to select an image file for text extraction.
Once an image is selected, a preview will be displayed in the application window.
Click the "PROCESS" button to extract text from the image using Tesseract OCR.
Extracted text will be shown in a new window.
The extracted text will also be saved as a .txt file in the current directory.

Acknowledgments
This application uses Tesseract OCR for text extraction.
Tkinter library is used for building the graphical user interface.





https://github.com/AnuragNagare/OCR/assets/85473989/f4d880a2-0bca-4c2a-90e8-2e9eb456a5f5




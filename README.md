# Image to Bangla Text (OCR) Text Converter

Image to Bangla Text (OCR) Text Converter is a Django-based web application that allows users to convert image files to text documents. It supports both the Bangla and English languages using the pytesseract library and provides an easy-to-use interface for seamless conversion.

## Features

- Converts image files to text documents
- Supports Bangla and English languages
- Easy-to-use interface
- Copy all texts and print functionalities after conversion
- UTF-8 text output for compatibility

## Prerequisites

### Windows Users

Before running the Django project, Windows users must install the Tesseract OCR software by following these steps:

1. Download the Tesseract OCR installer from [here](https://digi.bib.uni-mannheim.de/tesseract/tesseract-ocr-w64-setup-5.3.1.20230401.exe).
2. Run the downloaded installer and follow the installation instructions.
3. Ensure that Tesseract OCR is properly installed and added to the system's PATH.

### Linux and Other Users

Linux and other users should refer to the [Tesseract OCR Wiki](https://github.com/UB-Mannheim/tesseract/wiki) for installation instructions specific to their operating systems.

## Setup

To set up and run the Image to Bangla Text (OCR) Text Converter project, follow these steps:

1. Clone the project repository:
```bash
   git clone https://github.com/surajit-singha-sisir/Django-Project-Setup-Template.git
   ```
2. Navigate to the project directory:
```bash
   cd image-to-bangla-text
```   
3. Create a virtual environment:
```bash
   python -m venv venv
```

4. Activate the virtual environment:

- For Windows:

  ```
  venv\Scripts\activate
  ```

- For Linux and macOS:

  ```
  source venv/bin/activate
  ```

5. Install the required dependencies:
```bash
   pip install -r requirements.txt
```
6. Run database migrations:
```bash
   pip install -r requirements.txt
```
7. Start the development server:
```bash
   python manage.py runserver
```

8. Open your web browser and visit `http://localhost:8000` to access the Image to Bangla Text (OCR) Text Converter application.

## Usage

1. Upload an image file by clicking on the "Choose File" button.
2. Select the desired image file (supports various image formats) and click "Submit".
3. The image will be processed using OCR, extracting the text content.
4. The extracted text will be displayed on the screen, allowing you to copy the text or print it.
5. If the image contains both Bangla and English text, both will be accurately extracted.
6. You can perform multiple image-to-text conversions by repeating the above steps.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- [pytesseract](https://pypi.org/project/pytesseract/)
- [Pillow (Python Imaging Library)](https://python-pillow.org/)
- [Django](https://www.djangoproject.com/)
- [Tesseract OCR](https://github.com/tesseract-ocr/tesseract)

## Contributing

Contributions to the Image to Bangla Text (OCR) Text Converter project are always welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## Support

For any questions or support regarding the Image to Bangla Text (OCR) Text Converter project, please contact [project owner name] at [email@example.com].

Thank you for using the Image to Bangla Text (OCR) Text Converter!











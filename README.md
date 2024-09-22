# OCR Image Age Verifier

This project is a Flask web application that allows users to upload an image containing text. The application uses Tesseract OCR to extract the date of birth (DOB) from the text and calculates the user's age. Based on the age, users are either welcomed or informed they are under 18.

## Features
- Image upload functionality.
- Text extraction from images using Tesseract OCR.
- Automatic date of birth (DOB) detection from the extracted text.
- Age calculation based on the extracted DOB.
- Conditional redirection based on whether the user is 18 or older.

## Prerequisites

To run this project, you'll need the following:

- [Python 3.x](https://www.python.org/downloads/)
- [Tesseract OCR](https://github.com/UB-Mannheim/tesseract/wiki) (installed on your machine)
- Required Python libraries:
  - Flask
  - Pillow
  - pytesseract

## Installation

1. **Clone this repository**:
    ```bash
    git clone https://github.com/your-username/flask-tesseract-age-verifier.git
    cd flask-tesseract-age-verifier
    ```

2. **Install the required Python libraries**:
    ```bash
    pip install Flask Pillow pytesseract
    ```

3. **Install Tesseract OCR**:

   - **Windows**: Download and install Tesseract from [here](https://github.com/UB-Mannheim/tesseract/wiki).
   - **macOS**: Use Homebrew to install:
     ```bash
     brew install tesseract
     ```
   - **Linux (Ubuntu)**:
     ```bash
     sudo apt update
     sudo apt install tesseract-ocr
     ```

4. **Add Tesseract to your `PATH`** (Windows only):
   - During installation, make sure to check the option to "Add Tesseract to the system PATH."
   - If you've already installed Tesseract, you can manually add its installation directory (usually `C:\Program Files\Tesseract-OCR`) to your system's `PATH` environment variable.

5. **Verify Tesseract Installation**:
    Open a terminal or command prompt and run:
    ```bash
    tesseract --version
    ```

## Usage

1. **Run the Flask application**:
    ```bash
    python app.py
    ```
2. **Open your web browser** and navigate to:
http://127.0.0.1:5000/

3. **Upload an image** containing a date of birth, and the application will:
- Extract text using Tesseract OCR.
- Detect the date of birth from the extracted text.
- Calculate the user's age.
- Redirect the user based on whether they are 18 or older.

## License

This project is licensed under the MIT License.

## [+] Find Me On :

[![Github](https://img.shields.io/badge/Instagram-Rahul-pink?style=for-the-badge&logo=instagram)](https://www.instagram.com/rahulgarg__09?igsh=MTh5ZnNmMnRicGw5dg==)
[![Github](https://img.shields.io/badge/TELEGRAM-Rahul-blue?style=for-the-badge&logo=telegram)](https://t.me/cyberrj09)


## Visiter
<img src="https://profile-counter.glitch.me/rahulgarg2206/count.svg" alt="Visitors">

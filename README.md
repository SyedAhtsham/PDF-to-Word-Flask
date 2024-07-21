# PDF to Word Converter

![Cover Image](https://github.com/SyedAhtsham/PDF-to-Word-Flask/blob/main/cover.png)

This project is a web application built with Flask that converts PDF files to Word documents. The application extracts text and images from PDF files and outputs them into a Word document format (.docx).

## Table of Contents
- [Demo](#demo)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Deployment](#deployment)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Demo
You can access the live demo of the application [here](https://pdf-to-word-flask-1.onrender.com).

## Features
- Upload a PDF file and convert it to a Word document.
- Extract text and images from each page of the PDF.
- Download the converted Word document.

## Technologies Used
- **Flask**: Web framework for Python
- **PyMuPDF (fitz)**: Library for working with PDF files
- **python-docx**: Library for creating and updating Microsoft Word (.docx) files
- **HTML/CSS**: Frontend design

## Installation
To run this project locally, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/SyedAhtsham/PDF-to-Word-Flask.git
    ```

2. Navigate to the project directory:
    ```sh
    cd PDF-to-Word-Flask
    ```

3. Create and activate a virtual environment:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

4. Install dependencies:
    ```sh
    pip install -r requirements.txt
    ```

5. Run the Flask application:
    ```sh
    flask run
    ```

The web app should now be running on `http://localhost:5000`.

## Usage
- Navigate to the home page.
- Upload a PDF file using the file input form.
- Click the convert button to convert the PDF to a Word document.
- Download the converted Word document.

## Deployment
This application is deployed on Render. You can access it [here](https://pdf-to-word-flask-1.onrender.com).

To deploy your own instance:

1. Create an account on [Render](https://render.com).
2. Create a new web service and connect it to your GitHub repository.
3. Set the build and start commands:
    - **Build Command**: `pip install -r requirements.txt`
    - **Start Command**: `gunicorn app:app`
4. Deploy the service.

Render will automatically build and deploy your application.

## Project Structure
```plaintext
PDF-to-Word-Flask/
├── templates/
│   └── index.html
├── app.py
├── requirements.txt
├── cover.png
├── README.md
└── ...

```

Contributing
Contributions are welcome! If you have any suggestions or improvements, please create an issue or submit a pull request.

License
NA

Contact
For any questions or feedback, please contact us at syedahtshamqau@gmail.com.

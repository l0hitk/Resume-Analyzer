# Smart Resume Analyser App

## Overview
This Python project aims to analyze resumes in PDF format using the PDFMiner library for extracting text from PDF files and PyResparser for parsing and extracting relevant information such as skills, experience, and education from resumes.

## Features
- User's & Admin Section
- Resume Score
- Resume writing Tips suggestions

## Usage
- Clone my repository.
- Open CMD in working directory.
- Run following command.
  ```
  pip install -r requirements.txt
  ```
- `App.py` is the main Python file of Streamlit Web-Application. 
- Download XAMPP or any other control panel, and turn on the Apache & SQL service.
- To run app, write following command in CMD. or use any IDE.
  ```
  streamlit run App.py
  ```
- `Uploaded_Resumes` folder is contaning the user's uploaded resumes.
- Admin side credentials is `qwert123` and password is `147258369`. 

## Acknowledgements
- The PyResparser library by Omkar Pathak for providing resume parsing capabilities.
- The PDFMiner library contributors for enabling PDF text extraction programmatically.

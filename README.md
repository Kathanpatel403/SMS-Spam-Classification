# SMS Spam Classifier

Welcome to the SMS Spam Classifier project! This project is designed to efficiently predict whether an SMS message is spam or not using Python and its powerful libraries.

## Working demo of website:
Link: https://drive.google.com/file/d/1NmCCVOHLnZ55WH5oybzzhv-i53B1E2Co/view?usp=drive_link

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)

## Introduction
The SMS Spam Classifier is a machine learning project that classifies SMS messages as either "spam" or "ham" (non-spam). The model is trained using a dataset of labeled SMS messages and leverages the Term Frequency-Inverse Document Frequency (TF-IDF) vectorizer to transform the text data into numerical features. The project employs various Python libraries for data processing, visualization, natural language processing, and deployment using Streamlit.

## Features
- Efficiently classifies SMS messages as spam or ham.
- Utilizes TF-IDF vectorizer for text feature extraction.
- Interactive web application for SMS spam classification using Streamlit.

## Installation
To run the project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/Kathanpatel403/Sms-Spam-Classifier.git
    cd Sms-Spam-Classifier
    ```

2. Create a virtual environment:
    ```bash
    python -m venv env
    env\Scripts\activate
    ```
4. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
To start the Streamlit web application, run the following command:
```bash
streamlit run app.py

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
# Chat with Multiple PDFs - OpenAI, Langchian and Streamlit Integration

This Python script enables users to interactively ask questions from multiple uploaded PDF documents using the OpenAI GPT-3 language model. The application is built using Streamlit, a popular Python library for creating web applications.

## Deployed Application

The application is deployed on Streamlit Cloud. You can access it [here](https://chat-with-multiple-pdfs-langchian-openai-and-app.streamlit.app/).

## Features

**OpenAI GPT-3 Integration**: Utilizes OpenAI's GPT-3 model for answering user queries related to the content of uploaded PDF documents.

**PDF Text Extraction**: Extracts text content from uploaded PDF files using `PyPDF2`.

**Chunking and Vectorization**: Splits the extracted text into chunks and creates a vector store using `langchain` and `FAISS` for efficient search and retrieval.

**Conversational Interface**: Employs a conversational chain for maintaining context between user queries across multiple PDF documents.
Streamlit UI: Provides a user-friendly interface powered by Streamlit, allowing users to input their OpenAI API key, upload PDFs, and ask questions.

## Requirements

Python 3.7 or higher
Libraries:'streamlit',, `PyPDF2`, `langchain`, `FAISS`

## Usage

1. **Set up Environment**

    ```bash
    pip install -r requirements.txt
    ```

2. **Run the application.**

    ```bash
    streamlit main.py
    ```

3. **Obtaining OpenAI API Key**

To use this application, you'll need an OpenAI API key. Here's how you can obtain it:

1. Visit the [OpenAI website](https://openai.com/).
2. Sign in or create an account if you're a new user.
3. Once logged in, navigate to your account settings or API dashboard.
4. Find or generate your API key. It will usually be a long string of characters.
5. Copy the API key and paste it into the 'Enter your OpenAI API key' field in the application.


4. **Interacting with the Application**

Input your OpenAI API key in the provided field.
Upload multiple PDF documents.
Ask questions related to the uploaded PDFs in the text input field provided.
Click "Process" to handle the user query based on the uploaded documents.

## Screenshots

[App Interface 1](https://github.com/akshxyjagtap/Chat-with-Multiple-PDFs-OpenAI-and-Streamlit-Integration/blob/a222260626e340a8c50fc98b8515b1547094ca0a/data/Screenshot%202023-11-16%20122410.png?raw=true)


[App Interface 2](https://github.com/akshxyjagtap/Ask-form-PDF-using-langchain/blob/a222260626e340a8c50fc98b8515b1547094ca0a/data/Screenshot%202023-11-16%20122509.png)

## Important Notes

Ensure a stable internet connection to interact with the OpenAI GPT-3.5 API.
The OpenAI API key is sensitive. Keep it confidential, and avoid sharing it publicly.

## Contributing

Contributions are welcome! Feel free to fork the repository, make enhancements, and create pull requests to improve the functionality or user experience of the application.

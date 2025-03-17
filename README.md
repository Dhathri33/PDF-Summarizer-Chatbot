# PDF Summarizer and Chatbot using LLaMa2 in Streamlit

## Project Overview

The PDF Summarizer Chatbot is a user-friendly application that allows you to upload PDF documents and receive concise summaries generated using advanced Large Language Models (LLMs). This project leverages the power of Natural Language Processing (NLP) to extract meaningful insights from textual data, making document analysis faster and more efficient.

## Project Purpose

I used **Replicate**, which provides **free** cloud API services with open-source models like **LLaMa2**. The open-source Python framework **Streamlit** is used to deploy the model into an interactive web app.

## Features

- **PDF Parsing**: Extract text from PDF files using PyPDF2.
- **AI-Powered Summarization**: Summaries are generated using the Llama 2 model, renowned for its state-of-the-art performance in NLP tasks.
- **Interactive User Interface**: Built with Streamlit, providing an intuitive platform for users to upload files and receive outputs.
- **Themes**: Support light and dark themes for user convenience.
- **API Integration**: Utilizes the Replicate API for seamless communication with the LLM backend.

## Getting Started

1. Clone the repository
2. Install dependencies
3. Set Up Replicate API Key
   Obtain your Replicate API key from [replicate.com](replicate.com) and add it to `secrets.toml` file in the `.streamlit` folder:
4. Run the application
   ```
   streamlit run app.py
   ```

## Acknowledgments

- Meta AI for Llama 2.
- Replicate for their API services.
- Streamlit and PyPDF2 for simplifying the development process.
- Data Professor (https://github.com/dataprofessor) for tutorials and project inspiration

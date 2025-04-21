# PDF RAG ChatBot with Llama3.2 and StreamLit

PDFChatBot is a Python-based chatbot designed to answer questions based on the content of uploaded PDF files. It utilizes the Gradio library for creating a user-friendly interface and LangChain for natural language processing.

## Technologies Used 🚀
* Llama3.2
* ChromaDB
* ollama
* Streamlit

## Features ⭐
* Process PDF files and extract information for answering questions.
* Maintain chat history and provide detailed explanations.
* Generate responses using a Prompt.
* Display resource passages from pdf, from which response is retrived and generated

## Prerequisites 📋
Before running the ChatBot, ensure that you have the required dependencies installed. You can install them using the following command:
```
pip install -r requirements.txt
```

## Usage 📚
1. Upload a PDF file using the "📁 Upload PDF" button.
2. Enter your questions in the text box.
3. Click the "Send" button to submit your question.
4. View the resource passages in the interface.

## Running Locally 💻
To run the PDF Interaction ChatBot, execute the following command:

```
streamlit run app.py
```

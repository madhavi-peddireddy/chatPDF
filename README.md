# ChatPDF-Langchain


This application allows you to upload a PDF and ask questions about it using natural language. The application uses a LLM to generate a response about your PDF. The LLM will not answer questions unrelated to the document.

## How it works

![alt text](https://bennycheung.github.io/images/ask-a-book-questions-with-langchain-openai/Ask_Book_Questions_Workflow.jpg)


## Installation

To install the repository, please clone this repository and install the requirements:

```
pip install -r requirements.txt
```
You will also need to add your OpenAI API key to the `.env` file.

## Usage

To use the application, run the `app.py` file with the streamlit CLI (after having installed streamlit): 

```
streamlit run app.py
```



[Reference](https://bennycheung.github.io/ask-a-book-questions-with-langchain-openai)
 

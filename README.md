# Question Answering with PDF using LLMs

The "Questions Answering with PDF using LLMs" project aims to build a system that can extract information from PDF documents and provide accurate answers to user queries using large language models (LLMs). This solution leverages Retrieval-Augmented Generation (RAG) techniques to enhance the response quality by combining the power of LLMs with document retrieval methods. By processing data stored in PDFs, the system retrieves relevant sections and integrates them with the LLM for generating context-aware answers.

## Key Components
1. PDF Parsing and Extraction
2. Embedding Storage
3. Retrieval-Augmented Generation (RAG) Implementation
4. LLM Integration
5. Query Answering Workflow
6. User Interface

## Technology Used
1. Python
2. Langchain
3. Hugging Face (Embeddings)
4. Groq (API Key, LLMs)
5. Chroma (Vector DataBase)
6. Streamlit

## Installation 
To install the repository, please clone this repository and install the requirements:

```pip install -r requirements.txt```


## Usage
To run this application, run app.py using Streamlit as 

```streamlit run app.py```

You need to provide a GROQ Api Key first. Then you can upload any pdfs and extract the information. 


## Contact 
For any feedback or queries, please reach out to me at [LinkedIn](https://www.linkedin.com/in/krishnakumaragrawal/)

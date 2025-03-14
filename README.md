# PDF LLM Question Answer and Summarizer

## Project Summary

This project is a web application that allows users to interact with PDF documents using Large Language Models (LLMs). The application enables the user to upload a PDF, summarize its content, and ask specific questions about it. It integrates multiple technologies such as Streamlit for the frontend, FastAPI for backend API connections, LiteLLM for interacting with LLMs, and cloud-based storage and hosting solutions for scalability. The system uses Redis for communication between FastAPI and other services, providing a seamless user experience for document analysis and question answering.

Supported LLMs:
- **GPT-4o**
- **Gemini**
- **Grok**
- **Claude**
- **DeepSeek**

## Live Demo

You can try the live demo of the application here:  
**https://damgassignment4-dvnn8diaea6xjifv7hfxbp.streamlit.app**  


## Key Features

- **PDF Upload:** Upload PDF files for processing and analysis.
- **Document Summarization:** Automatically generate summaries of PDF content using LLMs.
- **Question Answering:** Ask specific questions about the document and receive answers based on the content.
- **LLM Integration:** Choose from various LLMs (GPT-4o, Gemini, Grok, Claude, DeepSeek) for summarization and question-answering via LiteLLM.
- **PDF Content Selection:** Select from previously parsed PDF files or upload new ones for analysis.
- **User-Friendly Interface:** The frontend is built using Streamlit to ensure ease of use.
- **Scalable Architecture:** FastAPI handles backend services, while GCP hosts the FastAPI endpoints for scalability.
- **Efficient API Management:** LiteLLM simplifies interactions with LLM providers.
- **Cloud Hosting & Storage:** AWS S3 is used for storage, and GCP hosts the FastAPI endpoints for better scalability and reliability.
- **Dockerized Deployment:** All components are containerized with Docker and deployed to the cloud, ensuring consistent environments across development and production.

## Technologies Used

- **Streamlit:** For creating the frontend interface that allows users to interact with the application.
- **FastAPI:** For creating the REST API endpoints to manage PDF uploads, summarization, and Q&A functionalities.
- **LiteLLM:** To interface with LLMs (GPT-4o, Gemini, Grok, Claude, DeepSeek) for document summarization and answering user questions.
- **AWS S3:** For storing PDF files securely in the cloud.
- **GCP (Google Cloud Platform):** For hosting FastAPI endpoints, ensuring the application is scalable and accessible.
- **Docker:** To containerize the application and deploy it in a cloud environment, ensuring a portable and reproducible environment.
- **Redis:** For handling communication between FastAPI and other services, improving scalability and performance.
- **PDF Parsing Libraries:** Libraries such as PyMuPDF, PDFMiner, or PyPDF2 can be used to extract text content from PDF files.

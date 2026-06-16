# CHATBOT-FOR-GENERAL-HEALTH-QUERIES

## Project Overview

This project implements an AI-powered healthcare chatbot capable of answering general health-related queries using information extracted from medical documents. The chatbot retrieves relevant information from a knowledge base created from medical PDF documents and generates responses using Google's Generative AI.

The system follows a Retrieval-Augmented Generation (RAG) approach, combining document retrieval with large language models to provide context-aware responses.

---

## Features

* Answers general health-related questions.
* Uses medical PDF documents as the knowledge source.
* Extracts and processes text from PDF files.
* Splits documents into manageable chunks.
* Generates semantic embeddings using Sentence Transformers.
* Stores embeddings in ChromaDB vector database.
* Retrieves relevant information based on user queries.
* Uses Google Generative AI to generate responses.
* Supports multiple medical domains including:

  * Asthma
  * Diabetes
  * Hypertension

---

## Technologies Used

* Python
* Google Colab
* PyPDF
* ChromaDB
* Sentence Transformers
* LangChain Text Splitters
* Google Generative AI

---

## Project Structure

```
CHATBOT-FOR-GENERAL-HEALTH-QUERIES/
│
├── snlp.ipynb
├── asthma.pdf
├── diabetes.pdf
├── hypertension.pdf
├── requirements.txt
└── README.md
```

---

## Workflow

1. Load medical PDF documents.
2. Extract text from the PDFs.
3. Split extracted text into chunks.
4. Generate embeddings using Sentence Transformers.
5. Store embeddings in ChromaDB.
6. Accept user queries.
7. Retrieve relevant document chunks.
8. Generate responses using Google Generative AI.

---

## How to Run

1. Clone the repository.

```bash
git clone https://github.com/Deepa-12345678/CHATBOT-FOR-GENERAL-HEALTH-QUERIES.git
```

2. Open the notebook in Google Colab.

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Upload the required PDF documents.

5. Configure your Google Generative AI API key.

6. Run all notebook cells.

7. Enter health-related queries to interact with the chatbot.

---

## Disclaimer

This chatbot is developed for educational and research purposes only. It is not intended to replace professional medical advice, diagnosis, or treatment. Always consult qualified healthcare professionals for medical concerns.

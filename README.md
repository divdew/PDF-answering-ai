# PDF-answering-ai

The project "Answering AI" aims to develop a system that allows users to query a PDF document and receive accurate and contextually relevant responses. By leveraging natural language processing (NLP) techniques, the system extracts text from a PDF, processes it, and answers user queries based on the extracted content. This report details the development process, methodologies employed, and the final implementation of the Answering AI system.

Objectives
Text Extraction: Extract text content from PDF documents.
Text Preprocessing: Clean and preprocess the extracted text for analysis.
Word Embedding: Utilize word embedding techniques to convert text into numerical vectors.
Question Answering: Develop a mechanism to answer queries based on the text content.
User Interface: Create a user-friendly interface for interacting with the system.

Methodology
1. Text Extraction
The text extraction phase involves parsing the PDF to retrieve its text content. This is achieved using the PyMuPDF library, which provides robust tools for handling PDF files.
2. Text Preprocessing
Preprocessing involves converting the text to a format suitable for analysis. This includes tokenization, lowercasing, and removing punctuation and numbers.
3. Word Embedding
Word embedding translates text into numerical vectors, capturing semantic relationships between words. gensim's Word2Vec model is employed for this purpose.
4. Question Answering
The core functionality involves answering user queries by identifying the most relevant part of the text. Cosine similarity between the query vector and context vectors determines the best match.
5. User Interface
A simple web interface using Flask allows users to interact with the system, ask questions, and view answers.

#method to run
download the files.
putting file path in jupiter notebook and writing your question, run the notebook 
your answer will be available

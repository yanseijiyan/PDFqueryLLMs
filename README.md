# PDF Query using Large Language Models (LLMs)

This project demonstrates how to extract text from a PDF document, split it into smaller chunks, and perform queries using large language models (LLMs) and similarity search.

## Overview

The goal of this project is to facilitate searching and querying information within PDF documents using state-of-the-art natural language processing (NLP) techniques. It leverages the following key components:

- **PDF Extraction**: The PyPDF2 library is used to extract text from PDF documents.
- **Text Chunking**: The extracted text is split into smaller chunks for efficient processing.
- **OpenAI LLMs**: OpenAI's large language models (LLMs) are used to perform question answering and semantic similarity tasks.
- **FAISS for Similarity Search**: FAISS is utilized for efficient similarity search of text chunks.
- **TikToken (Optional)**: The TikToken library, if available, can be used for working with the TikTok API (optional dependency).

## Setup and Installation

1. **Clone the Repository**: Clone this repository to your local machine using the following command:

    ```bash
    git clone https://github.com/yanseijiyan/PDFqueryLLMs.git
    ```

2. **Install Dependencies**: Install the required Python packages by running the following commands:

    ```bash
    pip install -r requirements.txt
    ```

3. **Set Up OpenAI API Key**: Replace the placeholder API key in the environment variable `OPENAI_API_KEY` with your actual OpenAI API key.

4. **Run the Code**: Execute the provided Jupyter Notebook (`PDF_Query_LLM.ipynb`) to see the project in action.

## Usage

1. **Extract Text from PDF**: Provide the path to the PDF document you want to analyze in the notebook and execute the cells to extract text.

2. **Query and Search**: Use the notebook to query the extracted text using natural language queries. The system will return relevant sections from the document based on the queries.

3. **Experiment and Customize**: Feel free to experiment with different PDF documents, queries, and configurations to tailor the system to your needs.

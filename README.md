# PDF Text Extraction and Embedding
This repository provides a Python script for extracting text from a PDF and creating embeddings using OpenAI's API. The script uses the Langchain library to extract text from the PDF and then uses OpenAI's API to generate embeddings.

## Installation
To install the necessary packages, use the commands below:

    pip install langchain pymupdf openai pinecone-client tiktoken
  
## Usage
Replace the `OPENAI_API_KEY` placeholder in the script with your OpenAI API key.
Set the PDF URL you want to process in the `PyMuPDFLoader()` function.

This code will extract text from the PDF and create embeddings using OpenAI's API.

Note: You need to have an account with OpenAI to obtain an API key.

## License

This script is open-source and licensed under the MIT License. For more details, check the [LICENSE](LICENSE) file.

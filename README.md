# Packaged Food Label Reviewer

This project aims to develop an LLM-based assistant to provide reviews for packaged food based on ingredient information and content from labels. The assistant and help user evaluates the healthiness of the product based on Indian standards of healthy ingredient levels.
You can access the Google Colab notebook for this project [here](<https://colab.research.google.com/drive/1Xe06aVYuW9VsnXJUjZYBmlVxEUSUwFwd?usp=sharing>).

## Features
- **OCR Integration**: Extracts text from images of food labels using OCR technology.
- **LLM Assistant**: Utilizes Llama 3 as underlying LLM using and Groq LPU api 
- **Knowledge-Aware Retrieval-Augmented Generation (RAG)**: Incorporates contextual information to enhance the quality and accuracy of responses.
- **Vector Store and DB**: Manages and retrieves documents using FAISS and Qdrant for efficient vector-based search and retrieval.

## Future and ongoing work 
- **API genration**: Genrating apis incorporating OCR, RAG, GORQ api using langserve
- Genrating UI with API integration and hosting for cloud

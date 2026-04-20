# PDF Search Engine with Elasticsearch

This project implements a simple document search engine using Python and Elasticsearch. It extracts text from a PDF file, processes it into paragraphs, and indexes them for efficient keyword-based search.

## 🚀 Features

- Extract text from PDF files
- Split content into paragraphs
- Index data into Elasticsearch
- Perform keyword-based search queries

## 🛠️ Technologies Used

- Python
- Elasticsearch
- PyPDF
- Regex

## ⚙️ Setup

1. Install dependencies:

    ```bash
    pip install pypdf elasticsearch
    ```

2. Run Elasticsearch locally:
   
    ```bash
   docker run -p 9200:9200 -e "discovery.type=single-node" elasticsearch:8.0.0
    ```

4. Make sure Elasticsearch is running at:
   
    ```http://localhost:9200```

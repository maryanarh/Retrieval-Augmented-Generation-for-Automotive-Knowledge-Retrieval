# Retrieval-Augmented-Generation-for-Automotive-Knowledge-Retrieval

An intelligent **Retrieval-Augmented Generation (RAG)** application designed for automotive dealerships that combines semantic search with Large Language Models (LLMs) to provide accurate, context-aware responses regarding vehicle inventory, specifications, pricing, and dealership information.


## Project Overview

Traditional chatbots rely solely on pretrained language models, which may generate inaccurate or outdated information. This project implements a Retrieval-Augmented Generation (RAG) architecture that retrieves relevant dealership documents from a vector database before generating responses.


The workflow consists of:

1. Preparing dealership knowledge
2. Converting documents into vector embeddings
3. Storing embeddings inside ChromaDB
4. Performing semantic similarity search
5. Passing retrieved context to a Large Language Model
6. Generating context-aware responses

This approach significantly improves answer reliability while remaining scalable for real-world dealership applications.

---

## Features
- Semantic vehicle search using embeddings
- Retrieval-Augmented Generation (RAG)
- ChromaDB vector database integration
- Hugging Face Transformer models
- SentenceTransformer embeddings
- Interactive Gradio interface
- QR code generation
- Data visualization and evaluation
- Modular and extensible architecture
- GPU support (when available)

---

## Technologies Used

| Category | Technologies |
|----------|--------------|
| Programming | Python |
| Machine Learning | Transformers, Sentence Transformers |
| Vector Database | ChromaDB |
| Deep Learning | PyTorch |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib |
| Interface | Gradio |
| Image Processing | Pillow |
| QR Code Generation | qrcode |

---

## Example Workflow

1. Load dealership dataset
2. Generate text embeddings
3. Store vectors in ChromaDB
4. Query the vector database
5. Retrieve the most relevant dealership information
6. Generate an AI-powered response
7. Display results through Gradio

---

## Installation

```bash
git clone https://github.com/maryanarh/Retrieval-Augmented-Generation-for-Automotive-Knowledge-Retrieval
cd Retrieval-Augmented-Generation-for-Automotive-Knowledge-Retrieval
pip install -r requirements.txt
```

Run:


Open `RAG_Model.ipynb`.


## Potential Applications

- AI Sales Assistant
- Vehicle Recommendation System
- Customer Support Chatbot
- Automotive Knowledge Base
- Intelligent Inventory Search
- Dealer Information Assistant

---


## Learning Outcomes

This project demonstrates practical implementation of:

- Retrieval-Augmented Generation (RAG)
- Semantic Search
- Vector Databases
- Sentence Embeddings
- Large Language Models
- Information Retrieval
- AI-powered Question Answering
- Interactive Machine Learning Applications

---

## License
This project is released under the MIT License.

---

## Author

Developed as part of a practical exploration into Retrieval-Augmented Generation systems and modern AI applications for intelligent customer support.

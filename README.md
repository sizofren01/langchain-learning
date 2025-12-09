📘 LangChain Learning Repository

A structured and practical learning journey covering LangChain, LLMs, data ingestion, text processing, embeddings, vector databases, and the fundamentals required to build modern AI applications such as RAG, chatbots, and summarizers.

This repo contains hands-on notebooks, examples, and notes from my personal study and practice with LangChain.

📂 Repository Structure

Each folder represents a key stage of the LLM pipeline.

01 — Data Ingestion

Learn how to load and extract data from multiple sources:

PDF ingestion

Text documents

Web pages

YouTube transcripts

Directory loaders

Preprocessing raw text

02 — Data Transformation

Transform raw text into usable chunks:

Text cleaning

RecursiveCharacterTextSplitter

Character splitter

HTML/JSON splitters

Understanding chunk size, overlap, and tokenization

03 — Embeddings

Convert text into vector form for semantic tasks:

HuggingFace embeddings

Ollama embeddings

Sentence Transformers

Embedding dimensions & similarity metrics

04 — Vector Databases

Store and retrieve embeddings for semantic search:

Chroma DB

FAISS Index

Adding documents

Running queries

Building the foundation of a RAG system

🎯 Purpose of This Repository

This repo is a learning-oriented notebook collection, meant to demonstrate mastery of:

RAG Foundations

LangChain Components

Vector Databases

Semantic Search

Data Pipelines

Text Processing for AI

Embedding-based retrieval

It is not a final project — but rather a structured knowledge base showing all concepts learned along the way.

🛠 Technologies Used

LangChain

LangChain Community Tools

LangChain Groq

HuggingFace Embeddings

ChromaDB

FAISS

PyMuPDF (PDF extraction)

BeautifulSoup (HTML parsing)

Sentence Transformers

Python Dotenv

📦 Installation

Create a Python environment (optional):

python -m venv venv
source venv/bin/activate  # macOS/Linux
venv\Scripts\activate     # Windows


Install dependencies:

pip install -r requirements.txt

🚀 How to Use

Open any notebook using Jupyter or VS Code:

jupyter notebook


or simply use VS Code's built-in notebook support.

Explore concepts in order:

01 → 02 → 03 → 04


This progresses from data ingestion → splitting → embeddings → vector search.

📚 What I Learned

How to structure data for LLMs

How chunking affects accuracy

How embeddings work behind the scenes

How vector databases perform similarity search

Why RAG pipelines depend on clean chunking

The power of LangChain’s modular components

How different loaders and splitters work

⭐ Future Additions

RAG mini-project

Chatbot project

Semantic search example

Document QA pipeline using Groq models

Updated examples with latest LangChain versions

👨‍💻 Author

Shehjad Patel
AI Developer | Python | LangChain | LLM Engineering
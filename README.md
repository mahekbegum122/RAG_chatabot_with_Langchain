# Azure AI RAG Chatbot for Internship Assessment

### Student Information

- **Name:** Mahek Begum  
- **Final Year Student**  
- **Sreenidhi Institute of Science and Technology, Hyderabad**  
- **Branch:** Information Technology (CSE)

## Problem Statement
Students and interns often need to understand long technical or internship-related documents quickly. Manual reading and searching through PDFs is inefficient and time-consuming.

This project solves the problem by building an AI-powered chatbot that answers questions directly from documents using Retrieval-Augmented Generation (RAG).

## Target Users
- Engineering students
- Interns
- Freshers preparing for roles in AI, Data, and Software Engineering

## Why This Problem Was Chosen
As a student, I regularly work with lengthy internship descriptions, technical PDFs, and learning materials. This chatbot helps extract meaningful answers instantly using AI, improving productivity and understanding.

## Solution Overview
The chatbot uses a Retrieval-Augmented Generation (RAG) pipeline:
1. Documents are loaded and split into chunks
2. Embeddings are generated from text
3. Vectors are stored for similarity search
4. Relevant chunks are retrieved based on user queries
5. A Large Language Model generates contextual answers

## Tech Stack
- Python
- LangChain
- Streamlit
- OpenAI API (for development)
- Azure OpenAI / Azure AI Foundry (production-ready design)

## AI & Cloud Services Used
- **LLM**: GPT-based language models
- **Embeddings**: Text embeddings for semantic search
- **Vector Search**: FAISS-based retrieval
- **UI**: Streamlit web interface

## Azure AI Foundry Integration (Design Explanation)
This solution is designed to be deployed using:
- Azure AI Foundry for managing AI workflows
- Azure OpenAI Service for LLMs and embeddings
- Azure Blob Storage for document storage
- Azure AI Search for scalable vector indexing

Due to time and subscription constraints, the chatbot is demonstrated locally. However, the architecture is fully compatible with Azure AI Foundry and Azure OpenAI services.

## How to Run the Project
```bash
pip install -r requirements.txt
streamlit run RAG_app.py

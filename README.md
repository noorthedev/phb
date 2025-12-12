## Humanoid Robotics Documentation + RAG Chatbot (Robo-Doc)
This project provides a complete documentation website for Humanoid Robotics, built using Docusaurus, combined with an intelligent RAG (Retrieval-Augmented Generation) Chatbot named Robo-Doc.
Robo-Doc answers technical questions strictly from your project’s documents using LangChain, FAISS, and OpenAI embeddings.

## Contents
Overview
Project Structure
Requirements
Python RAG Setup
Creating the FAISS Index
Running the RAG Chatbot
Integrating Chatbot with Docusaurus
System Prompt (Chatbot Behavior)
Troubleshooting
License

## Overview

This project combines:
Docusaurus for documentation website
Python RAG pipeline for question-answering
Robo-Doc: An AI assistant that answers questions only from your custom dataset
FAISS vector index for fast document retrieval
OpenAI embeddings for semantic search
LangChain (latest version) modules

## Requirements
Node Requirements (for Docusaurus)
Node.js >= 18
npm >= 9

## Python Requirements
Python 3.10 or higher


## Integrating Chatbot with Docusaurus
You can embed the chatbot into your website using:
iframe
REST API (FastAPI backend)
Custom React component
API calls to the RAG backend


## System Prompt (Robo-Doc Behavior)

Robo-Doc uses the following system rules:
**You are an expert Q&A assistant for a Humanoid Robotics project.**
**Your name is "Robo-Doc".** 
**You answer strictly from the provided document context.**

**If context does not contain the answer:**
**"I do not have enough information in my knowledge base to answer that question."**

**Do not use external knowledge.
Do not guess.
Cite the source document when possible.**

## License

This project is for academic and research use.
You may modify and extend it according to your requirements.
If you want, I can also generate:

**requirements.txt
 Example data files
 Full FastAPI backend
 Docusaurus chat widget
 Deployment instructions (Vercel / Netlify + Python server)**

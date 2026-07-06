## RAG with Qwen Model

A Retrieval-Augmented Generation (RAG) pipeline using the open source `Qwen/Qwen2.5-0.5B-Instruct` model for text file question answering

### Overview

This project demonstrates the basic working of a RAG system using climate change data.

The document is divided into smaller chunks, converted into vector embeddings, and stored in a vector database. Relevant chunks are retrieved based on the user's query and passed to the Qwen language model to generate a context aware answer

### RAG Pipeline

Document

   ↓
   
Chunking

   ↓
   
Embeddings

   ↓
   
Vector Database

   ↓
   
Retrieval

   ↓
   
Prompt

   ↓
   
Qwen LLM

   ↓
   
Final Answer

### Purpose

The main purpose of this project is to understand the core architecture and workflow of Retrieval Augmented Generation without relying on paid APIs or large proprietary language models

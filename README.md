# Lexical and Semantic Search

This repository contains simple examples of **lexical search** and **semantic search** to demonstrate how modern information retrieval systems work.

The goal of this project is to show the difference between keyword-based search and meaning-based search.

I have used the Pinecone vector database for this project and followed examples from their official documentation and website.

---

## What is Lexical Search

Lexical search retrieves documents based on **exact words** present in the query.  
It matches tokens using techniques like term frequency and inverted indexes.

Example:  
A query for "policy cancellation" will only return results that contain those exact words.

Lexical search is best for identifiers, codes, and structured or legal text.

---

## What is Semantic Search

Semantic search retrieves documents based on **meaning** rather than exact words.  
It uses embedding models to convert text into vectors and compares them using similarity measures.

Example:  
A query for "policy cancellation" can also match "termination of coverage" because the meaning is similar.

Semantic search is best for natural language queries and question answering.

---

## Why Both Are Used

Lexical search provides precision through exact matches.  
Semantic search provides understanding through meaning.

Modern systems such as Retrieval-Augmented Generation (RAG) combine both to achieve accurate and reliable search results.

---

## Project Purpose

This project is intended to provide a clear and practical understanding of:
- How lexical search works
- How semantic search works
- Why both techniques are important in AI-powered search systems

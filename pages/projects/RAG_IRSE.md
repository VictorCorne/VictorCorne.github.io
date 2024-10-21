---
layout: post
scope: Large
title: Retrieval Augmented Generation (RAG) pipeline for scientific papers QA using sentence embeddings
status: 
skills: 
show_in_navigation: false
---


In this project for the information retrieval and search engines course at KULeuven, we developped a RAG ([retrieval augmented generation](https://en.wikipedia.org/wiki/Retrieval-augmented_generation)) pipeline to answer questions (in natural language) relating to scientific papers.
The assignment gave a lot of freedom in our implementation, and we used sentence transformers to embed papers and queries (more specifically the [multi-qa-MiniLM-L6-cos-v1](https://huggingface.co/sentence-transformers/multi-qa-MiniLM-L6-cos-v1) pretrained embedder for semantic search). We also implemented search acceleration and compression of the dataset.

- skills: Search Engines, Sentence Embeddings, Software Design
- status: Completed (June 2024)

![RAG Pipeline](https://knowledge.dataiku.com/latest/_images/rag-pipeline.png)
Illustration of a RAG pipeline (source: [https://knowledge.dataiku.com/latest/_images/rag-pipeline.png](https://knowledge.dataiku.com/latest/_images/rag-pipeline.png)).
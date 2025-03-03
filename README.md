## Retrieval-Augmented Generation (RAG) with ChromaDB

This project implements a RAG system to enhance question-answering on research papers. It:

- Indexes research paper chunks by generating possible questions for each chunk and storing them in ChromaDB as vector embeddings.
- Retrieves relevant chunks based on a user query using semantic similarity.
- Augments an LLM's response by providing the retrieved chunks as context.
- Handles unanswerable queries, instructing the model to return a special token (e.g., "IDK") when necessary.
- This approach improves accuracy and relevance in LLM-based Q&A by grounding responses in retrieved data. 

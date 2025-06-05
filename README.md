Document-Aware Chatbot using Groq + LangChain

## Objective

This project builds a high-performance **Generative AI chatbot** that can deeply understand and interact with a **long-form document**. It uses **Retrieval-Augmented Generation (RAG)** to answer free-form user queries with accurate, context-rich, and source-cited responses.

The solution is powered by **Groq AI’s ultra-fast LLM inference** and combines modern techniques like semantic chunking, vector-based retrieval and multi-turn memory.

## Tools & Libraries Used

| Tool/Library         | Purpose |
|----------------------|---------|
| **LangChain**        | RAG pipeline, chunking, chaining |
| **Groq (LLM)**       | Ultra-fast inference with `llama3-8b-8192` / `llama-3.3-70b-versatile` |
| **PyPDF2**           | PDF text extraction |
| **HuggingFace Embeddings** | Semantic vector embeddings (`all-MiniLM-L6-v2`) |
| **ChromaDB**         | Vector storage and retrieval |
| **Google Colab**     | Notebook interface |
| **OpenAI-compatible API** | Interface to Groq models |
| **Markdown / IPython** | Interactive output display |



## Sample Queries

- **What are Generative Models for Classification?**
- **What is Linear Discriminant Analysis?**
- **Explain the difference between LDA and QDA.**
- **What is GEN AI?**

Each response includes supporting context from the source document.


## How to Run (Google Colab)

1. Open the notebook: [Colab Notebook Link](https://colab.research.google.com/drive/1E4tLvqGsf9UCuP6BGZi4IJN4Zs9ibJAp?usp=sharing)
2. Upload `ISLP_website - Copy.pdf`
3. Run each cell step-by-step
4. Ask questions in natural language.

---

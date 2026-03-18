#  RAG Document Question Answering System

##  Overview
This project implements a Retrieval-Augmented Generation (RAG) pipeline to enable semantic search and natural language question answering over large unstructured document collections. Users can interact with documents conversationally and retrieve contextually relevant information in real time.

---

##  Features
- Semantic search across multiple documents  
- Support for large PDF files (100+ pages)  
- Intelligent text chunking for better retrieval accuracy  
- Fast similarity search using FAISS vector database  
- Natural language question answering  
- Fully offline system using local LLM (Ollama)  
- Scalable architecture for enterprise-style use cases  

---

##  Architecture

Documents (PDFs)  
↓  
Text Chunking  
↓  
Embeddings (HuggingFace)  
↓  
Vector Database (FAISS)  
↓  
Retriever  
↓  
Local LLM (Ollama)  
↓  
Answer Generation  

---

##  Tech Stack
- Python  
- LangChain  
- FAISS  
- HuggingFace Embeddings (sentence-transformers)  
- Ollama (Local LLM)  

---

##  Project Structure

rag-project  
│  
├── data/  
│   └── documents/        # Input PDF files  
│  
├── src/  
│   ├── ingest.py         # Document ingestion & embedding  
│   ├── app.py            # Q&A pipeline  
│  
├── faiss_index/          # Vector database  
├── requirements.txt  
├── README.md  

---

##  Example Usage

Query: What are the key policies in the document?  
Answer: The document outlines policies related to...  

---

##  Use Cases
- Enterprise document search systems  
- Knowledge management platforms  
- HR policy assistants  
- Research document exploration  

---

##  Key Highlights
- Built scalable RAG pipeline for semantic retrieval  
- Reduced manual document search effort  
- Enabled conversational access to large datasets  
- Designed for real-world enterprise use cases  

---

##  Future Improvements
- Add Streamlit UI for interactive chat  
- Support real-time document uploads  
- Implement hybrid search (keyword + semantic)  
- Add source citation for retrieved answers  

---

## 👩‍💻 Author
Prerna Choudhary 




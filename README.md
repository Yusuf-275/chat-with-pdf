# 📄 Chat with PDF – AI-Powered Document Q&A System

An AI-powered web application that allows users to chat with PDF documents. Upload one or more PDFs and ask natural language questions — the system retrieves relevant context using vector embeddings and generates accurate answers using an LLM.

This project was built as an academic mini-project to demonstrate practical usage of LLMs, embeddings, and retrieval-augmented generation (RAG).

## 🚀 Key Features

- 📂 Upload and process multiple PDF documents  
- 🔎 Semantic search over document content  
- 🧠 Context-aware answers using LLMs (RAG pipeline)  
- ⚡ Fast retrieval using vector database (FAISS/ChromaDB)  
- 🖥️ Clean web UI using Streamlit  
- 🔐 API key handling using environment variables  
- 🧩 Modular code structure for easy extension

  
## 🏗️ System Architecture (High-Level)

User Query
↓
Embedding Model
↓
Vector Store (FAISS / ChromaDB)
↓
Relevant Document Chunks
↓
LLM
↓
Final Answer


## 🧠 How the System Works (RAG Pipeline)

1. PDFs are uploaded by the user  
2. Text is extracted and split into chunks  
3. Each chunk is converted into vector embeddings  
4. Vectors are stored in a vector database  
5. User query is embedded  
6. Most relevant chunks are retrieved  
7. Retrieved context is passed to the LLM  
8. Final grounded answer is generated  


## 🛠️ Tech Stack

- Python  
- Streamlit  
- LangChain  
- FAISS / ChromaDB  
- PyPDF  
- OpenAI / Local LLM  
- python-dotenv  


## 📊 Use Cases

- Academic research assistant  
- Study material Q&A  
- Book & document exploration  
- College mini project  
- Personal AI document assistant  


## 🧪 Design Considerations

- Vector-based retrieval for fast search  
- Chunking to handle long documents  
- Environment variable security for API keys  
- Modular design for future extensions  
- RAG pipeline to reduce hallucinations  


## 🛣️ Future Improvements

- Citation highlighting  
- OCR for scanned PDFs  
- Chat history memory  
- Support for DOCX / TXT  
- Local LLM integration  
- Cloud deployment  
- User authentication  


## 🙌 Credits

This project was built with learning guidance from:

- Krish Naik — YouTube tutorials on AI & LangChain  
- Alejandro — YouTube tutorials on document Q&A systems  

All design choices and implementation decisions were done independently for learning and experimentation.


## ⭐ Support
If you find this useful, consider giving the repo a ⭐ — it really helps!

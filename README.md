# RAG Intelligent Retriever

A specialized Retrieval-Augmented Generation (RAG) system designed to answer complex questions based on the **Government of India Budget 2025-2026 Speech**. This project utilizes a modern AI stack to process PDF documents, create vector embeddings, and generate precise answers using the Groq LLM.



## 🚀 Features
* **PDF Processing**: Seamlessly loads and parses large PDF documents (e.g., the 60-page Budget Speech) using `PyPDFLoader`.
* **Intelligent Chunking**: Breaks down dense text into manageable segments with overlap to preserve context during retrieval.
* **Vector Search**: Uses `FAISS` and `HuggingFaceEmbeddings` for high-performance similarity searches.
* **Groq Integration**: Leverages the `llama3-8b-8192` model via Groq for rapid, high-quality response generation.
* **Context-Aware Chat**: A custom chatbot function that strictly references the provided knowledge base to ensure factual accuracy.

## 🛠️ Technical Stack
* **Orchestration**: LangChain
* **LLM**: Groq (Llama 3)
* **Embeddings**: HuggingFace (sentence-transformers)
* **Vector Database**: FAISS
* **Environment**: Python (with `python-dotenv` for API security)

## 📖 Usage

* Place your source PDF (e.g., budget_speech.pdf) in the project root.
* Open main.ipynb and run the cells to:
  -> Load and split the document.
  -> Initialize the vector store.
  -> Query the chatbot using the chatbot("your question") function.

## 📋 Installation

1. **Clone the repository**:
   ```bash
   git clone [https://github.com/PavithraPN-01/rag-intelligent-retriever.git](https://github.com/PavithraPN-01/rag-intelligent-retriever.git)
   cd rag-intelligent-retriever




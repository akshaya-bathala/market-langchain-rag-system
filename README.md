#  Market LangChain RAG System

##  Features

-  **Multi-URL Ingestion**  
  Extracts and processes content from multiple news/article URLs in real time.

-  **RAG-based Q&A System**  
  Combines retrieval + LLM reasoning to provide accurate, context-aware answers.

-  **Semantic Search with FAISS**  
  Efficient similarity search over embedded document chunks.

-  **Asynchronous Data Pipeline**  
  Built using `aiohttp` and `asyncio` for fast, parallel data fetching.

-  **Batch Embedding Optimization**  
  Improves performance and reduces API calls.

-  **Smart Text Chunking**  
  Uses `RecursiveCharacterTextSplitter` for optimal context preservation.

-  **Interactive UI**  
  Streamlit-based interface for easy querying and visualization.

---

##  Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/market-langchain-rag-system.git
cd market-langchain-rag-system
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Setup Environment Variables
```bash
OPENAI_API_KEY=your_api_key_here
```

### 4. Run the Application
```bash
streamlit run main.py
```

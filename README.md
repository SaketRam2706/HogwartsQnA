# **HogwartsQnA**  

🔮 **A Harry Potter-Themed RAG (Retrieval-Augmented Generation) Application**  

Answer questions about the magical world of Harry Potter using Mistral-7B and ChromaDB!  

---

## **✨ Features**  
- **Question-Answering**: Ask any question related to Harry Potter books and get accurate answers.  
- **Retrieval-Augmented Generation (RAG)**: Combines a vector database (ChromaDB) with Mistral-7B for context-aware responses.  
- **API Endpoint**: Flask-based `/ask` endpoint for easy integration.  
- **CORS Support**: Ready for frontend integration.  
- **Deployable on Vercel**: Pre-configured with `vercel.json`.  

---

## **🛠️ Tech Stack**  
- **Backend**: Flask  
- **Vector Database**: ChromaDB  
- **LLM**: Mistral-7B-Instruct-v0.2 (via Hugging Face)  
- **Embeddings**: `all-MiniLM-L6-v2` (Sentence Transformers)  
- **Deployment**: Vercel  

---

## **🚀 Installation & Setup**  

### **Prerequisites**  
- Python 3.8+  
- Hugging Face API Token (set as `HUGGINGFACE_API_TOKEN` in environment variables)  

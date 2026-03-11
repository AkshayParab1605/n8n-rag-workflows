# RAG Chatbot + Document Ingestion (n8n)

## Tech Stack
- 🤖 LLM: Groq (LLaMA 3.3 70B) — Free
- 🔢 Embeddings: Ollama (nomic-embed-text) — Free/Local
- 🗄️ Vector DB: Pinecone — Free Starter

## Setup
1. Import JSON into n8n
2. Add Groq API key
3. Add Pinecone API key (create index: 768 dims, cosine)
4. Set Ollama base URL: http://localhost:11434
5. Activate & upload documents via Form URL

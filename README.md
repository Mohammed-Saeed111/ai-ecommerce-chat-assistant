# AI-Powered E-commerce Chat Assistant with MongoDB & Gemini

<div align="center">

![AI Agent](https://img.shields.io/badge/AI-Agent-blue?style=for-the-badge&logo=openai)
![LangGraph](https://img.shields.io/badge/LangGraph-JS-green?style=for-the-badge)
![MongoDB](https://img.shields.io/badge/MongoDB-Atlas-green?style=for-the-badge&logo=mongodb)
![React](https://img.shields.io/badge/React-Frontend-blue?style=for-the-badge&logo=react)

An intelligent shopping assistant that thinks, acts, and adapts—powered by LangChain, MongoDB Atlas, and Google's Gemini model.


</div>


---

## ✨ Features
- Agentic behavior: autonomous tool selection & fallback logic  
- Semantic vector search + backup text search  
- Persistent context with thread-based chat sessions  
- Auto-generated synthetic product data  
- Full-stack setup: backend (Node.js) + potential frontend (React)

## 🛠 Tech Stack
- **Backend**: Node.js, LangChain (LangGraph), MongoDB Atlas  
- **AI Model**: Google Gemini via `@langchain/google-genai`  
- **Embeddings**: Vector search with MongoDB Atlas  
- **Parser**: `zod` + `StructuredOutputParser`

## 🚀 Getting Started

```bash
# 1. Clone the Repository
git clone https://github.com/Mohammed-Saeed111/ai-ecommerce-chat-assistant.git
cd ai-ecommerce-chat-assistant

# 2. Setup Backend
cd server
# Create .env file and add:
# MONGODB_URI=your_mongodb_connection_string
# GOOGLE_API_KEY=your_google_api_key
# PORT=5000

# 3. Install Dependencies
npm install

# 4. Seed the Database (to load sample products)
npm run seed

# 5. Start the Backend Server
npm run dev

# 6. Chat Endpoint (after server starts)
# Test using Postman or curl:
# POST http://localhost:5000/api/chat

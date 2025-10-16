# Insurellm-Chatbot

 ## Overview

Insurellm Chatbot is an intelligent conversational AI built using Retrieval-Augmented Generation (RAG) architecture.
It helps users learn about Insurellm, its products, and services in an interactive and context-aware manner.

The chatbot combines the power of Large Language Models (LLMs) with document retrieval to deliver accurate, grounded, and real-time responses from Insurellm’s internal data and knowledge sources.

### Key Features

💬 Contextual Conversations: Understands and maintains conversation flow.

📄 Document-Aware Responses: Uses RAG to retrieve relevant company information before generating answers.

🔎 Accurate & Explainable: Every response is grounded in real Insurellm data.

🌐 Modular Design: Easily extendable to other domains or companies.

🧩 Integration Ready: Deployable via web interface (Gradio, Streamlit, or Flask/Django).

### System Architecture

User Query
    ↓
Retriever (Vector Database: FAISS / Chroma / Pinecone)
    ↓
Relevant Contexts Retrieved
    ↓
LLM (OpenAI / HuggingFace Model)
    ↓
Response Generated with Context
    ↓
Displayed in Chat Interface



### Tech Stack

| Component           | Technology                               |
| ------------------- | ---------------------------------------- |
| **Frontend**        | Gradio                       |
| **Backend**         | Python                                   |
| **Core AI**         | LangChain                 |
| **LLM**             | GPT, or Llama 3                 |
| **Vector Store**    | FAISS / Chroma                 |
| **Data Source**     | Company Docs, PDFs, Knowledge Base       |
| **Embedding Model** | OpenAI Embeddings / SentenceTransformers |

### Example Conversation

<img width="764" height="443" alt="image" src="https://github.com/user-attachments/assets/7c444b72-d677-4b43-b98d-ae1db748ed13" />







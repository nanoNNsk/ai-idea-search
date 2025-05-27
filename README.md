# 🧠 AI Idea Search & Strategic Companion (AI Khongbeng)

This project combines **semantic idea retrieval** with **a strategic AI coach**  
designed to help users discover ideas, reflect deeply, and plan their lives intentionally — like having a personal “AI strategist” by your side.

---

## 🎯 Project Goals

### 1. AI Idea Search (Vector Semantic Search)
- Build a multilingual semantic search system using dense embedding models
- Utilize vector databases (e.g., Qdrant, FAISS) for efficient, meaningful retrieval
- Enable fuzzy & concept-based queries across use cases (e.g., e-commerce, content ideation)

### 2. Strategic Companion AI — *“AI Khongbeng”*
- Develop an AI that acts as a personal coach with emotional intelligence
- Uses LangChain, prompt engineering, and vector memory to simulate deep, reflective conversation
- Initial focus: goal setting, life planning, emotional support, and stress management

---

## 🧱 Tech Stack

| Component | Tools |
|-----------|-------|
| Embedding | `intfloat/multilingual-e5`, `SentenceTransformers` |
| Vector Search | `Qdrant`, `FAISS` |
| Language Models | `OpenAI (GPT-4)`, `Claude`, `HuggingFace Transformers` |
| Frameworks | `LangChain`, `Gradio`, `Streamlit` |
| Dev Tools | Python 3.10+, Jupyter, Colab, GitHub |

---

## 🚧 Project Structure

```bash
ai-idea-search/
├── prompts/               # Prompt templates for coaching & search
├── data/                  # User logs, test queries, coaching logs
├── notebooks/             # Experiments (retrieval, reflection, LangChain)
├── app/                   # UI prototype (Gradio or Streamlit)
├── docs/                  # Architecture, research, roadmap
└── README.md              # This file

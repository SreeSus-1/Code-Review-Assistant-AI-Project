# Code-Review-Assistant-AI-Project
Code Review Assistant that allows users to paste source code and receive: Bug detection  , Improvement suggestions ,  Optimization tips  , Best-practice recommendations

This project uses the DeepSeek-Coder model via Ollama to analyze code and provide
feedback, improvement suggestions, and bug fixes.

## Features
- Code-specialized LLM (DeepSeek-Coder)
- FastAPI backend
- Streamlit frontend
- Local inference with Ollama

## How to Run
1. Pull the model:
   ollama pull deepseek-coder
2. Start backend:
   uvicorn backend.main:app --reload
3. Start frontend:
   streamlit run frontend/app.py
4. Paste your code and get helpful feedback

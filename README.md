# RAG Chatbot

A FastAPI and Streamlit retrieval-augmented generation chatbot using LangChain, Gemini, and Chroma.

## Run the backend

```powershell
cd api
python -m uvicorn main:app --reload
```

## Run the Streamlit app

```powershell
python -m streamlit run app/streamlit_app.py
```

Set `GEMINI_API_KEY` in a local `.env` file before running the application. Do not commit `.env` or API keys.

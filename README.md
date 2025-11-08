# 🔍 Mini RAG Application

A simple **Retrieval-Augmented Generation (RAG)** demo built from scratch using open-source models. The goal is to retrieve the right information and generate accurate answers, without any external vector database.

 

## 🧠 How It Works

1. Knowledge base is embedded using **`all-MiniLM-L6-v2`**
2. A question is converted to an embedding and matched with stored documents
3. Relevant context is passed to **DistilBERT QA** to extract an answer
4. System evaluates both retrieval and answer accuracy

 

## ⚙️ Tech Used

* **Retriever:** `sentence-transformers/all-MiniLM-L6-v2`
* **Generator:** `distilbert-base-cased-distilled-squad`
* **Similarity:** Cosine similarity (no database)
* **Framework:** PyTorch

 

## 🚀 Run It

Just run the notebook top-to-bottom. No API keys, no GPUs required (optional if available).

 

## 💡 Future Improvements

* Add vector DB (Chroma, FAISS, Pinecone)
* Build UI (Streamlit/Gradio)
* Add source citation 
* Try stronger LLMs (Llama, Gemma, Mistral) 

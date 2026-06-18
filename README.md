# 🎥🌐 YouTube & Website RAG Chatbot

A GenAI-powered application that summarizes content from YouTube videos and websites, generates key takeaways, and allows users to ask questions using Retrieval-Augmented Generation (RAG).

## Features

* 📺 YouTube Video Summarization
* 🌐 Website Content Summarization
* 📝 Key Takeaways Generation
* 🤖 Question Answering using RAG
* 🔍 Semantic Search with FAISS
* 🧠 HuggingFace Embeddings
* ⚡ Groq LLM Integration
* 🎨 Streamlit User Interface

## Tech Stack

* Python
* Streamlit
* LangChain
* Groq (Llama 3.3 70B)
* HuggingFace Embeddings
* FAISS Vector Store
* UnstructuredURLLoader
* YoutubeLoader

## Project Workflow

User URL
↓
Load Content
↓
Website Loader / YouTube Loader
↓
Generate Summary
↓
Split Documents into Chunks
↓
Create Embeddings
↓
Store Vectors in FAISS
↓
Create Retriever
↓
Ask Questions
↓
Retrieve Relevant Chunks
↓
Generate Answer using LLM

## Installation

Clone the repository:

```bash
git clone https://github.com/princekumar1402/youtube-website-rag-chatbot.git
cd youtube-website-rag-chatbot
```

Create virtual environment:

```bash
python -m venv venv
```

Activate virtual environment:

Windows:

```bash
venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Environment Variables

Create a `.env` file:

```env
GROQ_API_KEY=your_groq_api_key
```

## Run the Application

```bash
streamlit run app.py
```

## Example Use Cases

* Summarize educational YouTube videos
* Summarize blog articles and documentation
* Chat with website content
* Extract key insights from long-form content

## Future Improvements

* Multiple URL Support
* Conversation Memory
* Source Citations
* PDF Export
* Chat History
* Advanced RAG Pipelines

## Author

Prince Kumar

B.Tech CSE, IIIT Kottayam

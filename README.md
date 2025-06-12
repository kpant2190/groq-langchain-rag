# 🧠 ChatGroqDame

ChatGroqDame is a Streamlit-based RAG (Retrieval-Augmented Generation) app using:

- 🧠 LangChain
- 🚀 Groq (for ultra-fast inference)
- 🤖 OpenAI (for embeddings)
- 🔍 FAISS (for vector similarity search)
- 🌐 WebBaseLoader (to load docs from LangSmith)
- ⚡ Streamlit (for interactive UI)

---

## 🛠️ Features

- Load and chunk LangSmith documentation
- Embed documents with OpenAI
- Store vectors in FAISS
- Use Groq’s Gemma 2 LLM for ultra-fast QA
- View document matches in an expandable UI

---

## 🔧 Setup

### 1. Clone the Repo

```bash
git clone https://github.com/YOUR_USERNAME/ChatGroqDame.git
cd ChatGroqDame
```

### 2. Create .env

```bash
cp .env.example .env
# Fill in your API keys inside .env
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the App

```bash
streamlit run app.py
```

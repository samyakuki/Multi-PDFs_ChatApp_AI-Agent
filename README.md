
# Multi-PDF Chat AI Agent 🤖📚

Chat seamlessly with multiple PDFs using LangChain, Google Gemini, and FAISS. Get accurate, context-aware responses from document data in real time.

---

## 📝 Description

Multi-PDF Chat AI Agent is a Streamlit-based web application that enables interactive conversations with multiple PDF documents. Users can upload documents, extract and process their content, and query them using a conversational AI interface.

---

## 🎯 How It Works

The application follows these steps:

1. **PDF Loading**
   Extracts text from multiple PDF documents.

2. **Text Chunking**
   Splits extracted text into manageable chunks for processing.

3. **Embedding Generation**
   Converts text chunks into vector representations using a language model.

4. **Similarity Search**
   Matches user queries with the most relevant chunks using FAISS.

5. **Response Generation**
   Generates accurate answers based on retrieved document context.

---

## 🎯 Key Features

* **Adaptive Chunking**
  Sliding window-based chunking for improved context handling.

* **Multi-Document QA**
  Supports querying across multiple PDFs with contextual understanding.

* **Conversational Interface**
  Real-time chat-based interaction with document data.

* **Flexible LLM Support**
  Compatible with models like Gemini, GPT, and other LLMs.

---

## 🌟 Tech Stack

* **Frontend**: Streamlit
* **Backend / AI Pipeline**: LangChain
* **LLM**: Google Gemini
* **Vector DB**: FAISS
* **PDF Processing**: PyPDF2
* **Environment Management**: python-dotenv

---

## ▶️ Installation

```bash
git clone <your-repo-link>
cd <repo-folder>
pip install -r requirements.txt
```

Create a `.env` file:

```env
GOOGLE_API_KEY=your_api_key_here
```

Run the application:

```bash
streamlit run app.py
```

---

## 💡 Usage

1. Upload one or more PDF documents
2. Process the documents
3. Ask questions in natural language
4. Receive context-aware responses based on document content

---


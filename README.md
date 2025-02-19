# QA-CHATBOT-WITH-DOCUMENT

A **GitHub README** for your project should be **clear, structured, and informative**. Here’s a well-organized **README.md** template for your **Conversational RAG with PDF and Chat History** project:  

---

## **Conversational RAG with PDF & Chat History 📚🤖**  

### **Overview**  
This project implements a **Conversational Retrieval-Augmented Generation (RAG) system** that allows users to:  
✅ **Upload PDF documents**  
✅ **Ask questions about the content**  
✅ **Get AI-generated answers with context-awareness**  
✅ **Maintain chat history for better follow-up questions**  

Built with **Streamlit, LangChain, ChromaDB, Hugging Face Embeddings, and Groq’s LLM**.  

---

## **🚀 Features**  
✔ **Upload & Process PDFs**: Extracts and splits text for better searchability.  
✔ **Chat with Documents**: Ask context-aware questions and receive accurate answers.  
✔ **Persistent Chat History**: Stores interactions for smarter conversations.  
✔ **Fast & Scalable**: Uses **ChromaDB** for efficient document retrieval.  
✔ **Secure API Key Handling**: `.env` support for private keys.  

---

## **🛠️ Tech Stack**  
- **Frontend**: [Streamlit](https://streamlit.io/)  
- **LLM**: [Groq API (Gemma2-9b-It)](https://groq.com/)  
- **Embedding Model**: [Hugging Face MiniLM](https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2)  
- **Vector Database**: [ChromaDB](https://www.trychroma.com/)  
- **PDF Processing**: [PyPDFLoader](https://python.langchain.com/docs/integrations/document_loaders/pypdf)  
- **Environment Variables**: [Dotenv](https://pypi.org/project/python-dotenv/)  

---

---

## **💡 How It Works**  

1️⃣ **User uploads PDFs** → System extracts & stores content in ChromaDB.  
2️⃣ **User asks a question** → Context-aware retriever fetches relevant text.  
3️⃣ **Groq’s LLM generates a response** based on retrieved information.  
4️⃣ **Chat history is stored** for better conversation flow.  

---


## **🔧 Future Improvements**  
🚀 **Add support for multiple file formats (DOCX, TXT, etc.)**  
🔍 **Implement a more advanced document ranking strategy**  
📊 **Improve UI with response confidence scores**  

---



### **📜 License**  
This project is licensed under the **MIT License**.  

---

Would you like any modifications or additional sections? 🚀

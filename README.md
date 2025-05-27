# Chat with Your Documents

A no-code AI agent that enables natural-language Q&A over your own documents (PDFs, Word files, text archives) using n8n, OpenAI GPT-4o Mini, and Quadrant.

![image](https://github.com/user-attachments/assets/5822f1ee-5933-4103-9ea5-07e0b919b7f2)

## 🔍 Use Case Overview

Rabi needs to interact with a variety of document formats—PDFs, Word files, text archives—without hunting through folders. Instead, Rabi simply asks:

> “What’s the PTO policy in our employee handbook?”  
> “Show me the latest sales figures from the Q1 report.”

In seconds, the AI assistant retrieves the exact snippets—policy details, tables, clauses—so Alex can focus on insights rather than file management.

---

## 💡 Key Features

- ✅ **Natural-language understanding** with OpenAI’s GPT-4o Mini  
- ✅ **Ingestion & chunking** of PDFs, DOCX, and TXT files  
- ✅ **Embedding**: Convert text chunks into vector representations  
- ✅ **Vector storage & search** powered by Quadrant  
- ✅ **Contextual memory** for follow-up questions  
- ✅ **Extensible** to Slack, Microsoft Teams, or embedded in web apps  

---

## 🌍 Real-World Applications

- 📑 **HR Onboarding** – New hire Q&A on policies and benefits  
- ⚖️ **Legal & Compliance** – Instant lookup of contract clauses and guidelines  
- 📈 **Finance & Audit** – Query financial reports, statements, and footnotes  
- 💼 **Internal Knowledge Base** – Chat-style search of SOPs, wikis, and manuals  
- 🧰 **No-Code Teams** – Build document bots visually without writing ingestion code  

---

## 🛠️ Tech Stack

- 🔹 **n8n.io** – Visual workflow builder  
- 🔹 **OpenAI GPT-4o Mini** – Conversational intelligence  
- 🔹 **Quadrant** – Open-source vector database (free tier available)  
- 🔹 **LangChain Agent** – Tool orchestration & reasoning  
- 🔹 **Memory Node** – Tracks and preserves multi-turn context  

---

## 🔧 How It Works

1. **Document Ingestion**  
   Load PDFs, Word docs, and text files into the workflow.  
2. **Chunk & Embed**  
   Split content into coherent chunks and generate vector embeddings.  
3. **Vector Storage**  
   Insert embeddings and metadata (filename, page, section) into Quadrant.  
4. **Query Embedding**  
   Embed the user’s question into the same vector space.  
5. **Vector Search**  
   Retrieve the top-k most relevant chunks from Quadrant.  
6. **Answer Generation**  
   Combine retrieved context with the original query for GPT-4o Mini to craft a concise response.  
7. **Memory Recall**  
   Maintain dialogue history to support follow-up questions seamlessly.  

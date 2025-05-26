# Chat with Your Documents

A no-code AI agent that enables natural-language Q&A over your own documents (PDFs, Word files, text archives) using n8n, OpenAI GPT-4o Mini, and Quadrant.
![image](https://github.com/user-attachments/assets/5822f1ee-5933-4103-9ea5-07e0b919b7f2)



## 🔍 Use Case Overview

**Meet Rabi**, a new hire at Busy Bee Wealth Management. Instead of digging through folders or tagging teammates, Rabi simply asks:

> “What is the health insurance coverage?”  
> “How is overtime compensated?”

In seconds, the AI assistant retrieves precise answers—coverage types, deductibles, copays, limitations, and overtime rates—so Sam can focus on delivering value from day one.

---

## 🛠️ Technology Stack

- **n8n.io** – No-code workflow builder  
- **OpenAI GPT-4o Mini** – Conversational intelligence  
- **Quadrant** – Open-source vector database  
- **LangChain Agent** – Tool orchestration and reasoning  
- **Memory Node** – Context preservation across turns  

---

## 📂 Project Structure

```bash
chat-with-docs-n8n/
├── workflows/
│   └── chat-with-docs.json      # n8n workflow definition
├── docs/
│   └── architecture.png         # (Optional) diagram image
├── README.md                    # This file
└── LICENSE                      # MIT License

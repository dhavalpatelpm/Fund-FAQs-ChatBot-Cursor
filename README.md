Here is a **more “Top GitHub Project style” README** with **badges, cleaner structure, and better visual hierarchy**. This format is used by many **AI / ML repos that attract stars and recruiters**. ⭐

You can **paste this directly into `README.md`**.

---

# 🤖 Mutual Fund AI Assistant

### RAG-LLM Chatbot powered by Google Gemini

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![LLM](https://img.shields.io/badge/LLM-Google%20Gemini-orange)
![Architecture](https://img.shields.io/badge/Architecture-RAG-green)
![Status](https://img.shields.io/badge/Status-Active-success)
![License](https://img.shields.io/badge/License-MIT-yellow)

An **AI-powered Mutual Fund FAQ Chatbot** built using **Retrieval-Augmented Generation (RAG)** and **Google Gemini** that enables users to **query mutual fund scheme information across multiple AMCs using natural language.**

Instead of manually searching PDFs or AMC websites, users can **ask questions conversationally and receive accurate contextual responses instantly.**

---

# 🚀 Live Demo

Try the chatbot here 👇

🔗 [https://aistudio.google.com/apps/e5ce3e14-e9bc-4b33-9c22-37c12abef7fb?fullscreenApplet=true&showPreview=true&showAssistant=true](https://aistudio.google.com/apps/e5ce3e14-e9bc-4b33-9c22-37c12abef7fb?fullscreenApplet=true&showPreview=true&showAssistant=true)

---

# 🎯 Problem Statement

Investors and analysts often struggle with:

* Scattered mutual fund information across **multiple AMC websites**
* Long **scheme documents and PDFs**
* Manual search for **expense ratio, exit load, SIP limits, etc**

This project solves the problem by creating a **conversational AI assistant** capable of retrieving and explaining fund information instantly.

---

# ✨ Features

✅ Natural Language Querying
✅ Retrieval-Augmented Generation (RAG)
✅ Multi-AMC Scheme Coverage
✅ Contextual Answer Generation
✅ Faster Mutual Fund Data Discovery
✅ Gemini-powered Intelligent Responses

---

# 🧠 Example Queries

Users can ask questions like:

💰 What is the **expense ratio of SBI Small Cap Fund?**
📊 What is the **benchmark index for Axis Bluechip Fund?**
📉 What is the **exit load of Nippon India Growth Fund?**
🔒 Do **ELSS funds have a lock-in period?**
💳 What is the **minimum SIP amount for a mutual fund?**

---

# 🏗 System Architecture

```
                ┌──────────────────────┐
                │       User Query      │
                └──────────┬───────────┘
                           │
                           ▼
                ┌──────────────────────┐
                │   Chatbot Interface   │
                └──────────┬───────────┘
                           │
                           ▼
                ┌──────────────────────┐
                │   Query Processing    │
                └──────────┬───────────┘
                           │
                           ▼
                ┌──────────────────────┐
                │  Embedding Generator  │
                └──────────┬───────────┘
                           │
                           ▼
                ┌──────────────────────┐
                │   Vector Database     │
                │ (Mutual Fund Data)    │
                └──────────┬───────────┘
                           │
                    Retrieve Context
                           │
                           ▼
                ┌──────────────────────┐
                │   Google Gemini LLM   │
                └──────────┬───────────┘
                           │
                           ▼
                ┌──────────────────────┐
                │    Generated Answer   │
                └──────────────────────┘
```
<img width="1536" height="1024" alt="ChatGPT Image Mar 6, 2026, 10_07_22 AM" src="https://github.com/user-attachments/assets/56ab1b55-97e2-4a06-8c20-debbca5cf9f6" />

---

# 🔄 RAG Pipeline

The chatbot follows a **Retrieval-Augmented Generation pipeline**:

1️⃣ User submits a question
2️⃣ Query is converted into **vector embeddings**
3️⃣ Semantic search retrieves **relevant mutual fund data**
4️⃣ Retrieved context is passed to the **Gemini LLM**
5️⃣ Gemini generates a **context-aware response**
6️⃣ The answer is returned to the user

---

# ⚙️ Tech Stack

| Layer          | Technology                           |
| -------------- | ------------------------------------ |
| LLM            | Google Gemini                        |
| Architecture   | Retrieval Augmented Generation (RAG) |
| Language       | Python                               |
| Embeddings     | Vector Embedding Model               |
| Knowledge Base | Mutual Fund Scheme Data              |
| Interface      | Google AI Studio                     |

---

# 📂 Project Structure

```
mutual-fund-rag-chatbot
│
├── data/
│   └── mutual_fund_data.pdf
│
├── src/
│   ├── data_loader.py
│   ├── embeddings.py
│   ├── retriever.py
│   ├── rag_pipeline.py
│   └── chatbot.py
│
├── requirements.txt
└── README.md
```

---

# 🛠 Installation

### Clone the repository

```bash
git clone https://github.com/yourusername/mutual-fund-rag-chatbot.git
cd mutual-fund-rag-chatbot
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Add Gemini API Key

Create a `.env` file

```
GEMINI_API_KEY=your_api_key_here
```

### Run the application

```bash
python chatbot.py
```

---

# 📊 Potential Use Cases

🏦 Fintech platforms
📈 Investment advisory tools
🤖 Customer support chatbots for AMCs
📚 Financial education assistants
📊 Mutual fund research tools

---

# 🔮 Future Improvements

* Real-time **AMC data APIs**
* **SEBI / AMFI data integration**
* Portfolio analysis assistant
* Mutual fund comparison tool
* Web & WhatsApp chatbot integration
* Real-time NAV retrieval

---

# 👨‍💻 Author

**Dee**

Building **AI-powered Fintech solutions using LLMs, RAG, and intelligent automation.**

---

# ⭐ Support

If you found this project useful:

⭐ Star the repository
🍴 Fork it
🤝 Contribute to improve it

---

# 📢 Connect

If you’re working in **AI, Fintech, Product, or LLM applications**, feel free to connect and collaborate.


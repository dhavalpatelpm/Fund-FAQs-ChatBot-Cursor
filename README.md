🤖 Mutual Fund FAQ Chatbot (RAG + Google Gemini)

An AI-powered Mutual Fund FAQ Assistant built using Retrieval-Augmented Generation (RAG) and Google Gemini that allows users to query mutual fund scheme details across Asset Management Companies (AMCs).

Instead of manually browsing PDFs, fact sheets, or AMC websites, users can ask questions in natural language and receive contextual answers instantly.

Example queries:

What is the expense ratio of SBI Small Cap Fund?

What is the minimum SIP amount for Nippon India Growth Fund?

Does ELSS funds have a lock-in period?

What is the benchmark index for a scheme?

What is the exit load for a specific mutual fund?

The chatbot retrieves the most relevant information from the knowledge base and uses Google Gemini LLM to generate a contextual response.

🚀 Live Demo

Try the chatbot here:

👉 https://aistudio.google.com/apps/e5ce3e14-e9bc-4b33-9c22-37c12abef7fb?fullscreenApplet=true&showPreview=true&showAssistant=true

🧠 Key Features

✔ Natural language querying for mutual fund information
✔ Retrieval-Augmented Generation for accurate responses
✔ Covers multiple AMCs and schemes
✔ Context-aware answers powered by Google Gemini
✔ Reduces dependency on static documents and manual search

⚙️ Tech Stack
Component	Technology
LLM	Google Gemini
Architecture	Retrieval-Augmented Generation (RAG)
Data Source	Mutual Fund scheme data
Embedding	Vector embeddings for semantic search
Backend	Python
UI	AI Studio App Interface
🏗 System Architecture
                User Query
                     │
                     ▼
             Chatbot Interface
                     │
                     ▼
             Query Processing Layer
                     │
                     ▼
           Embedding Generation
                     │
                     ▼
              Vector Database
          (Mutual Fund Knowledge)
                     │
         Retrieve Relevant Documents
                     │
                     ▼
              Context Injection
                     │
                     ▼
             Google Gemini LLM
                     │
                     ▼
              Generated Answer
                     │
                     ▼
                User Response
🔄 RAG Workflow

1️⃣ User asks a question about a mutual fund
2️⃣ Query is converted into vector embeddings
3️⃣ System retrieves relevant fund information from the knowledge base
4️⃣ Retrieved data is added as context to the LLM prompt
5️⃣ Google Gemini generates a natural language response
6️⃣ Answer is returned to the user

📊 Example Queries
Query	Response
Expense ratio of SBI Small Cap Fund	Returns latest expense ratio
Lock-in period for ELSS funds	Explains 3-year lock-in
Minimum SIP for Axis Bluechip Fund	Returns SIP amount
Exit load for ICICI Prudential Fund	Shows exit load details
📂 Project Structure
mutual-fund-rag-chatbot
│
├── data/
│   ├── mutual_fund_schemes.pdf
│
├── embeddings/
│   ├── vector_store
│
├── src/
│   ├── data_loader.py
│   ├── embeddings.py
│   ├── retriever.py
│   ├── rag_pipeline.py
│   ├── chatbot.py
│
├── requirements.txt
├── README.md
🛠 Installation
1️⃣ Clone the repository
git clone https://github.com/yourusername/mutual-fund-rag-chatbot.git
cd mutual-fund-rag-chatbot
2️⃣ Install dependencies
pip install -r requirements.txt
3️⃣ Add your Gemini API Key

Create a .env file

GEMINI_API_KEY=your_api_key_here
4️⃣ Run the application
python chatbot.py
📈 Use Cases

Investor support chatbot

Financial advisory platforms

Mutual fund research tools

AMC customer support automation

Fintech AI assistants

🔮 Future Improvements

Real-time AMC data integration

SEBI / AMFI data pipeline

Portfolio analysis support

Scheme comparison assistant

WhatsApp / Web chatbot integration

👨‍💻 Author

Built by Dee

If you're exploring AI + Fintech solutions, feel free to connect or collaborate.

⭐ Support

If you found this project useful, consider starring the repository.

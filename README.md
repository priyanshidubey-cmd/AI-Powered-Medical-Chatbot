🧠 Medical Chatbot with LLM Integration

An AI-powered medical assistant chatbot designed to answer medical-related questions using advanced Large Language Models (LLMs). This project demonstrates how to build a domain-specific conversational AI using tools like LangChain, FAISS, and custom vector stores.

🚀 Features

🔎 Semantic search on custom medical documents

🧠 Context-aware conversations powered by LLMs

🗂️ FAISS-based vector store for efficient retrieval

⚙️ Easily expandable with new datasets

🧪 Educational prototype for digital health applications

🛠️ Tech Stack

Python 3.10+

LangChain

FAISS (Facebook AI Similarity Search)

OpenAI API (or compatible LLM)

📁 Project Structure
medical-chatbot/
├── data/                     # Medical documents for indexing
├── vectorstore/db_faiss/    # Saved vector index
├── medibot.py               # Main chatbot script
├── create_memory_for_llm.py # Builds the vector store
├── connect_memory_with_llm.py # Connects vector store to LLM
├── requirements.txt
├── Pipfile / Pipfile.lock
└── README.md

⚡ Quick Start

Clone the repo

git clone https://github.com/priyanshidubey-cmd/AI-Powered-Medical-Chatbot
cd medical-chatbot


Install dependencies
Using pip:

pip install -r requirements.txt


Add your medical data
Place your medical text files (e.g., .txt, .pdf) in the data/ folder.

Build the vector memory

python create_memory_for_llm.py


Run the chatbot

python medibot.py

📌 Notes

This project is intended for educational and research purposes only.

It is not a substitute for professional medical advice or diagnosis.

📝 License

MIT License

🙌 Acknowledgements

Built using LangChain
, FAISS
, and inspired by open-source community work in healthcare AI.

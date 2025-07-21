# natural-language-to-sql

# 🧠 Natural Language to SQL Query Chat App

This Streamlit-based application empowers users to explore database tables using natural language queries powered by Azure OpenAI and LlamaIndex. Built for interactive SQL generation, it's ideal for data analysts, engineers, and curious users who want instant insights from structured databases.

## 🚀 Features

- 💬 Chat-based SQL query assistant using Azure OpenAI
- 📊 Embedded database schema explorer (SQLite)
- 🔍 HuggingFace-based embedding model for enhanced accuracy
- ⚙️ Introspection of tables via SQLAlchemy
- 🧠 Supports semantic interpretation with LlamaIndex's NL-to-SQL engine

## 🔧 Requirements

- Python 3.9+
- Azure OpenAI account & credentials
- SQLite database (`ecommerce_platform1.db`)

Install dependencies:

```bash
pip install -r requirements.txt
```

🛠️ Usage
Start the Streamlit app:

```
streamlit run main.py

```

🧩 Powered By
- Streamlit
- LlamaIndex
- Azure OpenAI
- HuggingFace Embeddings


🔐 Note
This app does not generate or store data outside of your local environment. Your credentials should remain secured and never be hardcoded.


📄 License
MIT License — customize as needed.

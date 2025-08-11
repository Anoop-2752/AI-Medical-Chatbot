# 🩺 AI Medical Chatbot

An intelligent **AI-powered medical assistant** that helps answer general medical queries, provide healthcare information, and assist with symptom guidance.  
This project uses **Pinecone** for vector database storage and **Groq's LLaMA 3 model** (`llama3-70b-8192`) for fast, accurate responses.

⚠️ **Disclaimer:** This chatbot is for informational purposes only. It is **not** a substitute for professional medical advice, diagnosis, or treatment.

![Image](https://github.com/user-attachments/assets/3180a1c6-2a67-464f-ad21-3f1eef7e9682)

## 📌 Features

- **Natural Language Understanding** – Chat in plain language and get accurate responses.
- **Medical Knowledge Retrieval** – Uses Pinecone for semantic search on medical documents.
- **Fast LLM Responses** – Powered by Groq's `llama3-70b-8192` model.
- **Context-Aware Conversations** – Remembers conversation context for better replies.
- **Serverless Deployment** – Works with serverless Pinecone indexes.

## 🛠 Tech Stack

| Component              | Technology |
|------------------------|------------|
| **Language Model**     | Groq LLaMA 3 (`llama3-70b-8192`) |
| **Vector Database**    | Pinecone |
| **Framework**          | LangChain |
| **Programming Language** | Python |
| **Environment**        | Jupyter Notebook / Python Scripts |


## Build-a-Complete-Medical-Chatbot-with-LLMs-LangChain-Pinecone-Flask-AWS

### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n aimedibot python=3.10 -y
```

```bash
conda activate aimedibot
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```
### Create a `.env` file in the root directory and add your Pinecone & openai credentials as follows:

```ini
PINECONE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
GROQ_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```

```bash
# run the following command to store embeddings to pinecone
python store_index.py
```

```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up localhost:
```




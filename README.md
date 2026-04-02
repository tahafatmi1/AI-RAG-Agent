# 📄 RAG Agent – n8n Workflow

## 🔹 Project Description

**RAG Agent** is an **n8n workflow** designed to demonstrate a Retrieval-Augmented Generation (RAG) pipeline for AI-powered data analysis.
It can:

* Download documents from Google Drive
* Process and embed documents with OpenAI embeddings
* Store and query data in Supabase Vector Store
* Respond to chat queries using a custom AI agent
* Maintain conversation context using Postgres memory

This workflow is ideal for **AI + data automation projects**, personal portfolios, or learning how to integrate AI with workflow automation tools.

---

## 🛠️ Tools & Technologies Used

* **n8n** – Workflow automation platform
* **Google Drive Node** – Fetch files from Google Drive
* **Supabase Vector Store** – Store and query embeddings
* **OpenAI (Chat + Embeddings)** – Generate embeddings and AI responses
* **Postgres** – Maintain chat memory
* **LangChain nodes** – Connect AI with workflow nodes

---

## ⚙️ Features

* Automated document download and processing
* RAG pipeline for AI-assisted querying
* Chat-triggered AI agent
* Easy to extend with new data sources or AI models

---

## 📂 Setup / How to Use

### 1. Import Workflow

1. Clone or download this repository.
2. Open your n8n instance.
3. Go to `Workflows → Import` → Select `RAG Agent.json`

### 2. Add Credentials

After importing, add your own credentials for the following nodes:

* **Google Drive** – For file download
* **Supabase** – For vector store
* **OpenAI** – For embeddings and chat
* **Postgres** – For chat memory

> ⚠️ All credentials have been removed from this repo for safety.

### 3. Configure Nodes

* Replace `YOUR_GOOGLE_DRIVE_FILE_ID` and `YOUR_GOOGLE_DRIVE_URL` with your file information.
* Ensure your Supabase tables exist and match the workflow configuration.

### 4. Activate Workflow

* Set `active` to **true** in n8n.
* Test workflow by sending a chat message or manually executing it.

---


## 🔗 References

* [n8n Documentation](https://docs.n8n.io/)
* [LangChain Node Docs](https://docs.n8n.io/nodes/n8n-nodes-langchain/)
* [OpenAI API](https://platform.openai.com/docs/)
* [Supabase Docs](https://supabase.com/docs)

---

## 📌 License

MIT License – Free to use, modify, and share.


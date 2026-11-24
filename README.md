# Chatbot Using LangChain

A hands-on learning repository focused on building LLM-powered applications and chatbots using **LangChain** and different Large Language Model (LLM) providers. This repository contains implementations and experiments exploring how to build chatbot applications, work with language models, and understand the core components of the LangChain framework.

## 📌 Overview

This project explores the development of chatbot applications using LangChain and integrates different LLM providers to understand how language models can be used in Python applications.

The notebooks cover concepts such as connecting to LLMs, designing prompts, generating responses, and working with LangChain's core components.

## 🛠️ Technologies Used

- Python
- LangChain
- LangChain Core
- LangChain Community
- Google Gemini
- Groq
- Ollama
- Jupyter Notebook
- Python Dotenv

## 📚 Concepts Covered

- Integration of Large Language Models (LLMs)
- Chat model initialization and configuration
- Prompt engineering
- ChatPromptTemplate
- Managing model responses
- LangChain components and runnable workflows
- Working with different LLM providers
- Environment variables for API key management
- Experimenting with locally hosted language models using Ollama

## 📂 Project Structure

```text
chatbot_using_langchain/
│
├── chatbots.ipynb
├── gemini/
│   └── Getting_started.ipynb
├── ollama/
│   └── app.py
├── .env
├── .gitignore
├── requirements.txt
└── README.md
```

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/Shivangi42/chatbot_using_langchain.git
```

### 2. Navigate to the project directory

```bash
cd chatbot_using_langchain
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Configure environment variables

Create a `.env` file in the project root and add the API keys required by the notebooks.

```env
GROQ_API_KEY=your_groq_api_key
GOOGLE_API_KEY=your_google_api_key
```

Replace the placeholders with your own API keys. Never upload your `.env` file or expose API keys in notebooks.

## 🚀 Usage

- Open the notebooks using Jupyter Notebook or VS Code.
- Install the dependencies required for the notebook.
- Configure the necessary API keys in your `.env` file.
- Run the cells sequentially to explore the implementations and understand the workflow.

For locally hosted models, install Ollama and download the model required by your implementation before running it.

## 🎯 Purpose

The purpose of this repository is to strengthen practical understanding of LangChain and LLM application development through experimentation, implementation, and hands-on learning.

## 👩‍💻 Author

**Shivangi Soni**


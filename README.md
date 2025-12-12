# 🧪 Demo: Web Scraping + Local LLM with Ollama

A beginner-friendly walkthrough showing how to build a simple AI workflow using **Python**, **web scraping**, **OpenAI**, and a **locally running LLM (Llama 3.2 via Ollama)** — all inside a **Jupyter Notebook in Cursor**.

This demo helps you get started with AI development **without spending money**, using fully local inference once the model is downloaded.

---

## 🚀 What This Demo Covers

- Setting up a clean Python project  
- Using Jupyter Notebook inside Cursor  
- Connecting to OpenAI using an API key (optional)  
- Scraping website content with Python  
- Installing Ollama and running **Llama 3.2** locally  
- Switching your code from a cloud model → a local model  
- Running your entire web scraping workflow using a local LLM  

---

## 📂 Repository Contents

| File | Description |
|------|-------------|
| `demo1.ipynb` | Main notebook with step-by-step workflow |
| `requirements.txt` | Python dependencies |
| `pyproject.toml` | Optional project configuration |
| `.gitignore` | Version control ignore settings |

---

## 🛠️ Prerequisites

- Python 3.10+  
- Jupyter Notebook (built into Cursor)  
- Basic Python knowledge  
- (Optional) OpenAI API Key  
- Ollama installed and running locally  
  - Supports macOS, Windows, and Linux  

---

## 📥 Setup Guide

### 1. Clone the repository
git clone https://github.com/leelakrishnasarepalli/demo-ollama.git
cd demo-ollama

### 2. Install dependencies
pip install -r requirements.txt

### 3. Install & run Llama 3.2 using Ollama
ollama run llama3.2


This will download the local model and start the server.

### 4. Open the Notebook

Open demo1.ipynb in Cursor and run the cells sequentially.


# 🤖 Local LLM Chat — Streamlit + Ollama

This project is part of my **Generative AI Internship (Arch Technologies)**.

I built a simple chat interface using **Streamlit** that connects to a locally running LLM through **Ollama**.  
All AI processing runs **on the local machine** — nothing goes to the cloud.

---

## 🚀 Features

✅ Chat UI built with Streamlit  
✅ Uses Ollama local LLM (`llama3.2`)  
✅ Conversation history  
✅ Reset Chat button  
✅ Safe streaming response handling  
✅ Runs fully offline

---

## 🛠️ Tech Stack

- Python
- Streamlit
- Ollama
- Requests (API calls)
- Llama 3.2 Model

---

## 📦 Installation & Setup

### 1️⃣ Install Python (if not installed)
https://www.python.org/downloads/

---

### 2️⃣ Install Ollama

Download from:

https://ollama.com/download

Then pull the model:

```bash
ollama run llama3.2
```

(Wait for download to finish, then `/exit`.)

---

### 3️⃣ Install dependencies

```bash
pip install streamlit requests
```

---

### 4️⃣ Run the app

Inside the project folder, run:

```bash
python -m streamlit run app.py
```

Then open:

```
http://localhost:8501
```

---

## 🧠 How It Works

1️⃣ User types question in Streamlit  
2️⃣ Python sends POST request to:

```
http://localhost:11434/api/generate
```

3️⃣ Ollama generates answer locally  
4️⃣ Response is displayed in the chat interface

No external servers. Fully private.

---

## 📸 Screenshots

> (Add screenshots here)

- App UI
- Sample chat
- Reset button

---

## 🎥 Demo Video

A short demo video is available on LinkedIn:



---

## 📚 What I Learned

✔️ Working with local LLMs  
✔️ API integration  
✔️ Debugging streaming JSON  
✔️ Building UI with Streamlit  
✔️ Handling chat history state  

This project helped me understand real-world AI application workflows.

---

### 🙌 Internship

**Arch Technologies — Generative AI Internship**
Month 1 — Task 1: Streamlit + Ollama Interface

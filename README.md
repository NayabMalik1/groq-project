<<<<<<< HEAD
# groq-project
=======
Perfect 👍 Tumne 4 tasks complete kiye hain (Groq, Gemini APIs, Ollama, Summarization system). Har ek ke liye alag README bana dete hain jisme:

* **Project description**
* **Files structure**
* **Installation steps**
* **Running steps**

---

## 1️⃣ README for **Groq**

````markdown
# 🚀 Groq LLM Integration

This project demonstrates how to integrate **Groq API** with Python for running LLM queries locally.

---

## 📂 Files
- `test-groq.py` → Main script to test Groq API  
- `.env` → Stores API key (`GROQ_API_KEY`)  
- `requirements.txt` → Dependencies list  

---

## ⚙️ Installation
```bash
# Clone repository
git clone https://github.com/NayabMalik1/groq-project.git
cd groq-llm

# Create virtual environment
python -m venv venv
source venv/bin/activate   # (Linux/Mac)
venv\Scripts\activate      # (Windows)

# Install dependencies
pip install -r requirements.txt
````

Add your **Groq API Key** in `.env`:

```
GROQ_API_KEY=your_api_key_here
```

---
 
---

## 🔑 Create a Groq API Key
1. Go to [Groq Cloud](https://console.groq.com/keys).
2. Sign up or log in.
3. Click **Create API Key**.
4. Copy the generated key.
5. Save it in your environment:
   ```bash
   export GROQ_API_KEY="your_api_key_here"   # Linux / macOS
   setx GROQ_API_KEY "your_api_key_here"     # Windows (PowerShell)


## ▶️ Running

```bash
python test-groq.py
```

This will send a prompt to Groq API and return the model response.

````

---

>>>>>>> a29dcdd (Initial commit)

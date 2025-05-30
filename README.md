# 🤖 LangGraph Chatbot — Groq + LangGraph + Streamlit

This project demonstrates how to build an **LLM-powered chatbot** using:

- 🧠 [LangGraph](https://www.langgraph.dev/) for managing dynamic conversational flows
- ⚡ [Groq](https://console.groq.com/) for blazing-fast LLaMA 3 inference
- 🌐 A built-in Wikipedia query tool
- ➗ A custom arithmetic (multiplication) tool
- 💻 [Streamlit](https://streamlit.io/) as the interactive frontend

---

## 📊 Output Preview


## 📽️ Video Demo & Walkthrough

🎥 **Watch the full tutorial**:  
[👉 YouTube Video (Chatbot using langgraph)](https://your-youtube-link-here)

> Learn how this chatbot works under the hood and how to build one from scratch using LangGraph and Groq!

---

## 🔧 Features

- ✅ Powered by LLaMA 3 70B via Groq
- ✅ Dynamic tool usage via LangGraph flow
- ✅ Wikipedia tool integration for knowledge lookups
- ✅ Custom `multiply_numbers` tool
- ✅ Full Streamlit interface
- ✅ Shows step-by-step flow (JSON) and graph diagram

---

## 📦 Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/langgraph-chatbot.git
cd langgraph-chatbot
```

### 2. Create a virtual environment
```bash
python -m venv venv
source venv/bin/activate    # Windows
```
### 3. Install dependencies
```bash
pip install -r requirements.txt
```
Or manually:

```bash
pip install streamlit python-dotenv langchain langgraph langchain-community langchain-groq Pillow
```

### 4. Add your Groq API key

Create a .env file:

```bash
GROQ_API_KEY=your_groq_api_key
Get your Groq API key at https://console.groq.com/
```

## How to Run
```bash
streamlit run app.py
App will run at: http://localhost:8501
```


## Example Usage
Try prompts like:

```bash
"Who is A. P. J. Abdul Kalam?"
→ Wikipedia tool is used to fetch the summary.

"Multiply 21 and 7"
→ Custom multiplication tool is invoked.

"Tell me about ISRO"
→ Wikipedia tool gives insights.
```

### 👤 Author

Built with ❤️ by A. Venkatesh | AI Engineer

## 📢 Stay Connected

🌟 Star this repo if you like it

🍴 Fork and modify for your own use

🧠 [Follow on LinkedIn](https://your-youtube-link-here)

🎬 [Subscribe to Youtube](https://www.youtube.com/@avenkatesh0610)
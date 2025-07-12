
# 🤖 Conversational AI Agent with Tool Integration

This project is a lightweight conversational AI assistant built using **LangChain**, **LangGraph**, and **OpenAI**. It simulates a smart chatbot capable of performing arithmetic operations, greeting users, and responding in real-time using the ReAct (Reasoning + Acting) agent framework.

---

## 🔧 Features

- 🔄 **ReAct Agent** using LangGraph and LangChain
- 🧠 **LLM Integration** via OpenAI's ChatGPT models
- 🧮 **Custom Tools**: 
  - Calculator for basic arithmetic
  - Friendly Greeter
- 📜 Simple conversational flow with real-time response streaming

---

## 📁 Project Structure

```

project1/
│
├── main.py           # Main Python file to run the agent
├── .env              # Environment file storing OpenAI API key
└── README.md         # Project documentation

````

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/langchain-ai-agent.git
cd langchain-ai-agent
````

### 2. Create a `.env` File

Create a `.env` file in the root directory and add your OpenAI API key:

```
OPENAI_API_KEY=sk-xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
```

### 3. Install Dependencies

Make sure you're inside a virtual environment, then run:

```bash
uv venv  # or python -m venv .venv
uv pip install -r requirements.txt
```

If you're not using `uv`:

```bash
pip install langchain langgraph langchain-openai python-dotenv
```

### 4. Run the Application

```bash
uv run main.py
```

or

```bash
python main.py
```

---

## 🧠 Sample Interaction


Welcome! I'm your AI assistant. Type 'quit' to exit.
You can ask me to perform calculations or chat with me.

You: Say hello to Paul
Assistant: Hello Paul, I hope you are well today

You: What is the sum of 23 and 42?
Assistant: The sum of 23 and 42 is 65

---

## 📚 Tech Stack

* [LangChain](https://www.langchain.com/)
* [LangGraph](https://github.com/langchain-ai/langgraph)
* [OpenAI](https://platform.openai.com/)
* [Python Dotenv](https://pypi.org/project/python-dotenv/)
* Python 3.10+

---

## 🙋‍♂️ Author

**Paulin Arul**
Connect with me on [LinkedIn](https://www.linkedin.com/in/paulin-arul-674b10259/)



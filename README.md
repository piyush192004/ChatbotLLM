# ChatbotLLM 🤖

An experimental project exploring **LLM-powered chatbots using LangChain, LangGraph, and external tools**.  
The repository demonstrates how to build progressively more advanced AI assistants including:

- Basic LLM chatbots
- Tool‑augmented agents
- Human‑in‑the‑loop systems
- LangGraph debugging workflows

The goal of this project is to **learn and experiment with agentic AI systems and modern LLM frameworks**.

---

## 📂 Project Structure

```
ChatbotLLM/
│
├── 1 - BasicChatbot/
│   └── 1-basicchatbot.ipynb
├── 2 - HumanAssistance/
│   └── 2-humanintheloop.ipynb
├── 3 - Debugging/
|   └── .langgraph_api
│   └── debugging.ipynb
|   └── agent.py
|   └── langgraph.json
├── .env
├── .gitignore
├── .python-version
├── main.py
├── pyproject.toml
├── requirements.txt
├── uv.lock
└── README.md
```

### Folder Explanation

**1 - BasicChatbot**  
Contains simple chatbot implementations to understand how LLMs respond to prompts.

**2 - HumanAssistance**  
Demonstrates **human-in-the-loop AI workflows** where humans can intervene in agent decisions.

**3 - Debugging**  
Experiments with **LangGraph debugging tools and agent state tracing**.

---

## ⚙️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/piyush192004/ChatbotLLM.git
cd ChatbotLLM
```

### 2️⃣ Create Virtual Environment (uv)

```bash
uv venv --python 3.11
```

Activate (Windows):

```bash
.venv\Scripts\activate
```

### 3️⃣ Install Dependencies

```bash
uv sync
```

or

```bash
uv pip install -r requirements.txt
```

---

## 🔑 Environment Variables

Create a `.env` file in the root directory.

Example:

```
OPENAI_API_KEY=your_api_key
GROQ_API_KEY=your_api_key
TAVILY_API_KEY=your_api_key
```

---

## ▶️ Running the Project

Run the main script:

```bash
python main.py
```

---

### Running LangGraph Dev Server

```bash
langgraph dev
```

or

```bash
uv run langgraph dev
```

This launches **LangGraph Studio**, allowing you to visualize and debug agent workflows.

---

## 🧪 Example Use Cases

This repository demonstrates:

- Building **LLM-powered assistants**
- Integrating **external tools into LLM workflows**
- Creating **stateful agents**
- Using **human-in-the-loop workflows**
- Debugging **agent decision graphs**

---

## 📚 Learning Goals

This project explores concepts such as:

- Agentic AI
- Tool‑augmented LLMs
- Prompt engineering
- Graph-based agent workflows
- Debugging LLM agents

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

Feel free to:

- Fork the repo
- Open an issue
- Submit a pull request

---

## 📜 License

This project is for **educational and experimental purposes**.

---

## 👨‍💻 Author

**Piyush Kumar Singh**  

Aspiring Software Developer  
Interested in **AI Agents, LLM Systems, and Scalable AI Applications**

GitHub:  
https://github.com/piyush192004

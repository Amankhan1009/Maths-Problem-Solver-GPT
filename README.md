# 🧮 Text to Math Problem Solver & Data Search Assistant

A **Streamlit-based AI chatbot** that solves mathematical problems and answers knowledge-based questions using **LangChain agents**, **Groq LLMs**, and **Wikipedia search tools**.

The application uses the **Qwen3-32B language model from Groq** to perform reasoning, mathematical calculations, and information retrieval.

---

# 📌 Project Overview

This project is an **AI-powered assistant** capable of:

- Solving **mathematical problems**
- Providing **step-by-step reasoning**
- Answering **logic-based questions**
- Searching **Wikipedia for general knowledge**

The system integrates:

- **Streamlit** for the user interface
- **LangChain** for building AI agents
- **Groq API** for fast LLM inference
- **Wikipedia API** for knowledge retrieval

---

# 🚀 Features

- 🧮 Math Problem Solver  
- 🧠 Logical Reasoning Assistant  
- 🌐 Wikipedia Knowledge Search  
- ⚡ Fast AI responses using Groq  
- 💬 Interactive Chat Interface  
- 📚 Step-by-step explanations  

---

# 🏗️ Project Architecture
```bash
User Question
│
▼
Streamlit Interface
│
▼
LangChain Agent
│
├── Calculator Tool (LLMMathChain)
│
├── Wikipedia Tool
│
└── Reasoning Tool (LLMChain)
│
▼
Groq LLM (Qwen3-32B)
│
▼
Final Response Displayed in UI
```

---

# 🧰 Technologies Used

```bash
| Technology | Purpose |
|-----------|---------|
| Python | Programming language |
| Streamlit | Web application framework |
| LangChain | LLM orchestration |
| Groq API | Fast LLM inference |
| Qwen3-32B Model | Large language model |
| Wikipedia API | Knowledge retrieval |
```
---

# 📂 Project Structure
```bash
project-folder
│
├── app.py
├── requirements.txt
└── README.md
```


---

# ⚙️ Installation

## 1️⃣ Clone the Repository
```bash
git clone [https://github.com/yourusername/math-ai-assistant.git](https://github.com/Amankhan1009/Maths-Problem-Solver-GPT.git)

cd Maths-Problem-Solver-GPT
```

---

## 2️⃣ Create Virtual Environment
```bash
python -m venv venv
```


Activate environment

**Windows**
```bash
venv\Scripts\activate
```

**Linux / Mac**
```bash
source venv/bin/activate
```


---

## 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```


---

# 🔑 Groq API Key Setup

1. Go to **https://console.groq.com**
2. Create an account
3. Generate an **API Key**
4. Enter the key in the **Streamlit sidebar**

---

# ▶️ Running the Application

Run the Streamlit app:
```bash
streamlit run app.py
```

Then open the browser:
```bash
[http://localhost:8501](http://localhost:8501)


---

# 💬 Example Question
```bash
I have 5 bananas and 7 grapes. I eat 2 bananas and give away 3 grapes.
Then I buy a dozen apples and 2 packs of blueberries.
Each pack of blueberries contains 25 berries.

How many total pieces of fruit do I have?
```


The chatbot will:

1. Understand the question  
2. Perform calculations  
3. Provide a **step-by-step explanation**

---

# 🧠 Tools Used by the AI Agent

### 📚 Wikipedia Tool
Searches Wikipedia to answer **knowledge-based questions**.

### 🧮 Calculator Tool
Uses **LLMMathChain** to solve mathematical expressions.

### 🧠 Reasoning Tool
Handles **logic and explanation-based questions**.

---

# 🔮 Future Improvements

- Add **conversation memory**
- Add **document upload support**
- Improve **UI design**
- Support **multiple LLM models**
- Add **voice input**

---

# 👨‍💻 Author

**Md Aman Alam**

Machine Learning & AI Enthusiast

---

# 📜 License

This project is licensed under the **MIT License**.

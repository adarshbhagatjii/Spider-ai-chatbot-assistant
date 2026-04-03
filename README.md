# 🕷️ Spider AI – Role-Based Professional AI Assistant

Spider AI is a **Streamlit-based AI chatbot** powered by **Groq + LLaMA 3.3 (70B)** using **LangChain**.  
It dynamically adapts its behavior based on user-selected roles like **Teacher, Debugger, Analyst, Interview Coach, and more**.

---

## 📌 Live Demo

🔗 **Live Demo:** [spider-ai-chatbot-assistantr](https://spider-ai-chatbot-assistant.streamlit.app/))

---

## 🚀 Features
- 🎭 **Role-Based AI Behavior**
  - General Assistant
  - Teacher
  - Interview Coach
  - Debugger
  - Analyst
- 🧠 Powered by **LLaMA 3.3 (70B)** via Groq
- 💬 Real-time Chat Interface
- 🧑‍💻 User Personalization (Name-based interaction)
- 🎨 Modern UI with Custom Styling
- 🧾 Persistent Chat History (Session-based)
- ⚡ Fast Responses using Groq API

---

## 🛠️ Tech Stack
- **Frontend:** Streamlit  
- **Backend / LLM:** LangChain + Groq API  
- **Model:** llama-3.3-70b-versatile  
- **Environment Management:** Python Dotenv  

---

## 📂 Project Structure
``` 📁 Spider-AI
│── chatbot.py                # Main Streamlit Application
│── .env                  # API Keys 
│── requirements.txt      # Dependencies
│── README.md             # Project Documentation
```

---

## ▶️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/ats-resume-analyzer.git
cd ats-resume-analyzer
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the App

```bash
streamlit run app.py
```

---

## 💬 How It Works

1. User enters their name (User Verification)
2. Selects a role from sidebar
3. AI adapts its behavior using a custom prompt template
4. Chat history is maintained using Streamlit session state
5. Responses are generated via Groq LLM


---

## 🧠 Prompt Engineering
* The system uses a structured prompt:

* Defines AI identity (Spider AI)

* Injects selected role behavior

* Personalizes responses using user name

* Maintains conversation context

## 🎯 Use Cases

* 📚 Learning & Teaching Concepts

* 💼 Interview Preparation

* 🐞 Debugging Code

* 📊 Data Analysis Guidance

* 🤖 General AI Assistance

## 👨‍💻 Author

**Adarsh Bhagat**
🚀 Software Engineer | MERN Stack Developer | AI/ML Enthusiast

---

## 🌟 Future Enhancements

* 🔊 Voice Input / Output

* 📄 Chat Export (PDF/Markdown)

* 🌐 Multi-language Support

* 🧠 Memory Persistence (Database)

* 🔐 Authentication System

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork this repo and submit a PR.

---

## 📜 License

This project is licensed under the **MIT License**.

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!


# 🧠 AI Interview Tool

An interactive AI-powered mock interview app built with **Streamlit**, **OpenAI (GPT-4o)**, and **LangChain-style memory**, designed to simulate an HR interview experience. Users can enter personal details, and the chatbot will conduct a tailored 5-question interview, followed by smart feedback and a performance score.

[🌐 Live Demo on Streamlit Cloud]([https://interview-tools.streamlit.app](https://aung-interview-tools.streamlit.app/))  
*(Replace this link with your actual Streamlit Cloud URL)*

---

## 📌 Features

- 📝 Collects user information: name, experience, skills, role, and company
- 🤖 AI HR Interviewer asks 5 role-specific questions
- 💾 Uses memory to personalize the conversation
- 📊 Feedback and performance score (1–10) generated at the end
- 🖥️ Streamlit UI for easy use and fast prototyping
- 🔁 Option to restart the interview session

---

## 🚀 Demo Walkthrough

### Step 1: Fill in your interview details  
- Name  
- Experience  
- Skills  
- Target position and company  

### Step 2: AI Interview Simulation  
- The chatbot acts as a human HR interviewer  
- Asks 5 questions based on your input  
- Stores all interactions in session state  

### Step 3: Get Feedback  
- After 5 questions, press "Get Feedback"  
- Receive a performance score and improvement suggestions  

---

## 🧰 Tech Stack

- **Frontend/UI**: [Streamlit](https://streamlit.io/)
- **LLM**: [OpenAI GPT-4o](https://platform.openai.com/)
- **State Management**: Streamlit `session_state`
- **Chat Memory & Prompting**: Custom setup simulating LangChain-style context
- **Deployment**: [Streamlit Cloud](https://streamlit.io/cloud)

---

## 📦 Setup Instructions

1. **Clone the repository**

```bash
git clone https://github.com/aungkaungpyaepaing/interview-tools.git
cd interview-tools

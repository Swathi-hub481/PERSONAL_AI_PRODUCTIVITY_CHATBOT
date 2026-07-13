<div align="center">

# PERSONAL_AI_PRODUCTIVITY_CHATBOT

### AI-Powered Productivity & Automation Assistant

Build • Automate • Organize • Achieve More with Generative AI

![Python](https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-Web_App-FF4B4B?style=for-the-badge&logo=streamlit)
![OpenAI](https://img.shields.io/badge/OpenAI-GPT-black?style=for-the-badge&logo=openai)
![Gemini](https://img.shields.io/badge/Google-Gemini-4285F4?style=for-the-badge&logo=google)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

*A centralized AI-powered productivity platform that automates writing, planning, summarization, and content creation using Large Language Models (LLMs).*

</div>

---

#  Table of Contents

- Overview
- Objectives
- Key Features
- System Architecture
- Tech Stack
- Project Structure
- Installation
- Usage
- Application Workflow
- Modules
- Future Enhancements
- Learning Outcomes
- Contributing
- Author
- License

---

#  Overview

**PERSONAL_AI_PRODUCTIVITY_CHATBOT** is an AI-powered productivity assistant designed to simplify everyday work through Generative AI.

The application integrates multiple AI-powered productivity tools into a single platform, allowing users to generate professional emails, summarize documents, create meeting notes, improve writing, generate content, and organize daily tasks efficiently.

The project follows a modular architecture with a dedicated business logic layer, prompt engineering layer, and LLM API integration, making it scalable, maintainable, and easy to extend.

---

#  Objectives

The main objectives of this project are:

- Develop an intelligent AI productivity assistant.
- Automate repetitive daily tasks using LLMs.
- Demonstrate Prompt Engineering techniques.
- Build a clean and interactive Streamlit application.
- Improve productivity through AI automation.
- Showcase practical Generative AI application development.

---

#  Key Features

##  Email Generator

Generate professional emails within seconds.

✔ Business Emails

✔ Formal & Informal Emails

✔ Reply Emails

✔ Follow-up Emails

✔ Subject Line Suggestions

---

##  Email Summarizer

- Summarize long email conversations
- Extract key information
- Identify action items
- Save reading time

---

##  Meeting Notes Generator

- Convert meeting transcripts into structured notes
- Generate summaries
- Highlight important decisions
- Extract action items

---

##  PDF Notes Summarizer

- Upload PDF documents
- Generate concise summaries
- Extract key insights
- Improve learning efficiency

---

##  Content Creator

Generate AI-powered content including:

- Blog Posts
- Articles
- LinkedIn Posts
- Product Descriptions
- Marketing Content
- Social Media Captions

---

##  Grammar & Rewrite Assistant

Improve writing by:

- Grammar Correction
- Sentence Rewriting
- Tone Enhancement
- Professional Formatting

---

##  Task Planner

Generate:

- Daily Plans
- Weekly Plans
- Study Schedules
- Goal Roadmaps
- Project Task Lists

---

##  Prompt Engineering

- Optimized Prompt Templates
- Better AI Responses
- Structured Input Formatting
- Improved Context Management

---

#  System Architecture

```
                User
                  │
                  ▼
          Streamlit Interface
                  │
                  ▼
        Business Logic Layer
                  │
                  ▼
        Prompt Engineering Layer
                  │
                  ▼
            LLM API Client
                  │
                  ▼
      OpenAI GPT / Google Gemini
                  │
                  ▼
          AI Generated Response
                  │
                  ▼
          Streamlit Interface
```

---

#  Technology Stack

| Category | Technologies |
|----------|--------------|
| Programming Language | Python 3.11 |
| Frontend | Streamlit |
| AI Models | OpenAI GPT, Google Gemini |
| Prompt Engineering | Custom Prompt Templates |
| PDF Processing | PyPDF |
| Data Processing | Pandas |
| Environment Variables | Python-dotenv |
| Version Control | Git & GitHub |
| IDE | Visual Studio Code |

---

#  Project Structure

```
PERSONAL_AI_PRODUCTIVITY_CHATBOT/

│
├── 📁 assets/
│   ├── banner.png
│   ├── architecture.png
│   └── screenshots/
│
├── 📁 pages/
│   ├── Email_Generator.py
│   ├── Email_Summarizer.py
│   ├── Meeting_Notes.py
│   ├── PDF_Summarizer.py
│   ├── Content_Creator.py
│   ├── Grammar_Assistant.py
│   └── Task_Planner.py
│
├── 📁 utils/
│   ├── api_client.py
│   ├── prompts.py
│   ├── helper.py
│   ├── pdf_utils.py
│   └── constants.py
│
├── 📁 uploads/
├── 📁 data/
│
├── app.py
├── requirements.txt
├── .env.example
├── .gitignore
├── README.md
└── LICENSE
```

---

#  Installation

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/Swathi-hub481/PERSONAL_AI_PRODUCTIVITY_CHATBOT.git
```

---

## 2️⃣ Navigate to Project Directory

```bash
cd PERSONAL_AI_PRODUCTIVITY_CHATBOT
```

---

## 3️⃣ Create Virtual Environment

### Windows

```bash
python -m venv venv
```

---

## 4️⃣ Activate Virtual Environment

```bash
venv\Scripts\activate
```

---

## 5️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 6️⃣ Configure Environment Variables

Create a `.env` file in the project root.

```env
OPENAI_API_KEY=your_openai_api_key

GEMINI_API_KEY=your_gemini_api_key
```

---

## 7️⃣ Run the Application

```bash
streamlit run app.py
```

---

#  Application Workflow

```
User Input
     │
     ▼
Select Productivity Module
     │
     ▼
Prompt Engineering
     │
     ▼
LLM API Request
     │
     ▼
AI Model Processing
     │
     ▼
Generated Response
     │
     ▼
Display Results in Streamlit
```

---

#  Application Modules

| Module | Description |
|----------|-------------|
| 📧 Email Generator | Generate professional emails |
| 📩 Email Summarizer | Summarize lengthy emails |
| 📝 Meeting Notes Generator | Convert transcripts into structured notes |
| 📄 PDF Notes Summarizer | Upload and summarize PDF documents |
| ✍️ Content Creator | Generate blogs, articles, and social media content |
| 📖 Grammar Assistant | Rewrite and improve writing |
| ✅ Task Planner | Generate schedules and action plans |

---

#  Future Enhancements

- 🔐 User Authentication
- 💬 Chat History
- 🌍 Multi-language Support
- 🎤 Voice Assistant
- 📅 Calendar Integration
- 📧 Email Sending Integration
- 📂 Document Chat (RAG)
- 🧠 Memory-enabled AI Assistant
- ☁️ Cloud Deployment
- 📱 Mobile Responsive Interface
- 🤖 Multi-Agent AI Workflow

---

#  Learning Outcomes

Through this project, the following concepts were explored:

- Generative AI Application Development
- Large Language Model Integration
- Prompt Engineering
- Streamlit Web Development
- REST API Integration
- Modular Software Architecture
- Environment Variable Management
- Python Project Organization
- AI Productivity Automation

---

#  Contributing

Contributions are welcome!

If you'd like to contribute:

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push your branch
5. Submit a Pull Request

---

#  Author

## Mamidi Swathi

**B.Tech – Computer Science & Engineering**

**Skills**

- Python
- Generative AI
- Large Language Models
- Prompt Engineering
- Streamlit
- AI Automation

**GitHub**

https://github.com/Swathi-hub481

**LIVELINK**

.

---

#  Support

If you found this project useful,

 Star this repository

 Fork the repository

 Report issues

 Suggest new features

---

---

<div align="center">

###  If you like this project, don't forget to Star the Repository!

**Made with LOVE using Python, Streamlit, OpenAI, Gemini & Generative AI**

</div>

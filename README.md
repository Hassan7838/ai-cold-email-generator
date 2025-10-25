# ai-cold-email-generator
"AI-Powered Cold Email Generator for Job and Client Outreach"

This project showcases an **AI-powered application** that automatically generates personalized **cold emails** for **job applications, client outreach, or sales pitches**.  
Built using **OpenAI GPT API**, **LangChain**, and **ChromaDB**, this tool tailors messages based on the user’s **skills, role, and target company**, simulating the workflow of a modern AI assistant used in professional communication automation.

# Project Goal

To design a generative AI system that:
- Crafts professional, personalized cold emails based on user inputs.
- Stores user preferences and previous email data using a **vector database (ChromaDB)**.
- Demonstrates the integration of **LLMs (GPT / Llama)** into real-world applications for productivity automation.

# How It Works

### User Input
The system collects:
- **Job Title / Role**
- **Company Name**
- **User Skills or Resume Highlights**
- (Optional) Custom tone or style preference (e.g., formal, friendly, persuasive)

### LLM Processing
- Uses **LangChain** to structure the prompt and context.
- Connects to **OpenAI GPT-4 / GPT-3.5 API** (or compatible open-source LLMs like Llama 3).
- Generates a high-quality, personalized email with proper structure (greeting → body → closing).

### Knowledge Storage (ChromaDB)
- Stores and retrieves user-specific data such as:
  - Past companies contacted
  - Skills and preferences
- Enhances future personalization with retrieval-augmented generation (RAG).

### Streamlit Interface
- Provides an interactive UI where users can input details and instantly generate the email.
- Option to copy the email or export it to `.txt` / `.docx`.

# Tools and Technologies

| Category | Tools Used |
|-----------|-------------|
| **Frontend / UI** | Streamlit |
| **LLM Integration** | OpenAI GPT-4 / GPT-3.5, LangChain |
| **Data Storage** | ChromaDB (Vector Database) |
| **Backend** | Python |
| **Environment** | `.env` file for storing API keys |
| **Optional Models** | Llama 3, Gemini, Claude (for model flexibility) |

## Features
✅ Generate AI-personalized cold emails for job applications or client outreach  
✅ Adjustable tone and style (e.g., formal, friendly, confident)  
✅ Save user data and previous email history using **ChromaDB**  
✅ Export generated emails to text or document formats  
✅ Lightweight and deployable via **Streamlit Cloud** or **Hugging Face Spaces**

## Main Goal
-Learn LLM integration

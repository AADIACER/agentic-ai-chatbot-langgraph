# LangGraph Groq Agentic Chatbot

An experimental conversational AI chatbot built using **LangGraph, Groq and Streamlit**. The project explores stateful conversational workflows, message management and LLM integration, with plans to gradually introduce more advanced agentic capabilities.

**Project Status:** Under Development

## Current Features

- **LLM Integration:** Uses Groq API with the `openai/gpt-oss-20b` model.
- **LangGraph Workflow:** Implements a chatbot using `StateGraph`.
- **Message Management:** Maintains conversation messages using LangGraph's `add_messages`.
- **In-Memory Checkpointing:** Uses `MemorySaver` to maintain conversation state during runtime.
- **Streamlit Interface:** Provides a simple interactive chat interface.
- **Streaming Responses:** Displays LLM responses incrementally.

## Tech Stack

- Python
- LangGraph
- LangChain
- Groq API
- Streamlit
- Python Dotenv

## Project Structure

```text
LangGraph-Groq-Agentic-Chatbot/
│
├── agentic_chatbot_backend.py
├── streamlit_frontend.py
├── requirements.txt
├── .env.example
├── .gitignore
└── README.md
```

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/LangGraph-Groq-Agentic-Chatbot.git
cd LangGraph-Groq-Agentic-Chatbot
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

Activate it:

**Windows:**
```bash
.venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure environment variables

Create a `.env` file in the project root:

```env
GROQ_API_KEY=your_groq_api_key
```

Get your API key from [Groq Console](https://console.groq.com/).

### 5. Run the application

```bash
streamlit run streamlit_frontend.py
```

## Planned Improvements

The following features are potential future additions:

- LangSmith integration for tracing and observability.
- Human-in-the-loop (HITL) workflows.
- Tool calling and external tool integration.
- Conditional routing and more complex LangGraph workflows.
- Long-term memory and persistent conversation storage.
- Multi-agent workflows.
- Improved error handling and application reliability.

## Learning Objectives

This project is also an opportunity to explore:

- Building stateful applications with LangGraph.
- Integrating and working with LLM APIs.
- Managing conversational state and checkpoints.
- Implementing streaming responses.
- Gradually developing agentic AI systems.

## Note

This project is actively under development. Features listed under Planned Improvements have not yet been implemented and may change as development progresses.

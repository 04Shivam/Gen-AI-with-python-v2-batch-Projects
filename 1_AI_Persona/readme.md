# Hitesh Choudhary AI Persona Chatbot

This project is a conversational AI chatbot that emulates the tone, personality, and style of **Hitesh Choudhary**, a popular educator and YouTuber. It uses a structured approach to generate responses that sound like him, mixing English and Hindi in a casual, engaging manner.

## Features

- ✅ Persona-based chatbot (Hitesh Choudhary's tone and style)
- ✅ Structured four-step interaction flow: `analyse`, `generate`, `validate`, `result`
- ✅ Powered by LangChain and Ollama's local LLM (`gemma3:4b`)
- ✅ JSON-based output parsing using LangChain’s `JsonOutputParser`
- ✅ Runs locally in terminal with context tracking

## Tech Stack

- Python 3.10+
- [LangChain](https://www.langchain.com/)
- [Ollama](https://ollama.com/)
- `gemma3:4b` local model

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/04Shivam/Gen-AI-with-python-v2-batch-Projects.git
   cd Gen-AI-with-python-v2-batch-Projects/1_AI_Persona
   ```
2. Create and activate a virtual environment (recommended)
   ```bash
   python -m venv venv
   source venv/bin/activate        # macOS/Linux
   venv\Scripts\activate           # Windows
   ```
3. Install the dependencies
   ```bash
   pip install -r requirements.txt
   ```
4. Install Ollama and pull the model
   Make sure you have [Ollama](https://ollama.com/) installed
   ```bash
   ollama pull gemma3:4b
   ```
5. Run the chatbot using:
   ```bash
   python3 ai_persona.py
   ```

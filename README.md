# AgentMagic

A Python application using OpenAI agents for intelligent task handling.

## Setup

1. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

2. **Set up environment variables:**
   
   Create a `.env` file in the root directory with your OpenAI API key:
   ```
   OPENAI_API_KEY=your_actual_openai_api_key_here
   ```
   
   **Important:** Replace `your_actual_openai_api_key_here` with your real OpenAI API key.
   
   You can get your API key from: https://platform.openai.com/api-keys

3. **Run the application:**
   ```bash
   python app.py
   ```

## Environment Variables

- `OPENAI_API_KEY`: Your OpenAI API key (required)

## Features

- Homework detection guardrail
- Math tutor agent
- History tutor agent
- Intelligent triage system

## Security Note

The `.env` file is already included in `.gitignore` to prevent accidentally committing your API key to version control. 
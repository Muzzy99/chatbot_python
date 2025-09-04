# AI Chatbot with Google Gemini

A Flask-based AI chatbot application using Google's Gemini AI model.

## Features
- Real-time chat interface
- Chat history with SQLite database
- Google Gemini AI integration
- Beautiful web UI

## Setup
1. Clone the repository
2. Create virtual environment: `python -m venv venv`
3. Activate virtual environment: `source venv/bin/activate` (Linux/Mac) or `venv\Scripts\activate` (Windows)
4. Install dependencies: `pip install -r requirements.txt`
5. Set up API key: `echo "GOOGLE_API_KEY=your_api_key_here" > .env`
6. Run the application: `python app.py`
7. Open browser to: http://localhost:5000

## Requirements
- Python 3.8+
- Google Gemini API key
- Flask
- LangChain

## API Key Setup
Get your free API key from: https://aistudio.google.com/app/apikey

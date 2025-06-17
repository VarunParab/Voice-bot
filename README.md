# Voice Bot

A simple chat application using Groq's Llama 3B model with a modern React frontend and FastAPI backend.

## Prerequisites

- Python 3.8+
- Node.js 14+
- Groq API key

## Setup

1. Clone the repository
2. Set up the backend:
   ```bash
   cd backend
   pip install -r requirements.txt
   ```
   Create a `.env` file in the root directory with your Groq API key:
   ```
   GROQ_API_KEY=your_groq_api_key_here
   ```

3. Set up the frontend:
   ```bash
   cd frontend
   npm install
   ```

## Running the Application

1. Start the backend server:
   ```bash
   cd backend
   uvicorn main:app --reload
   ```

2. In a new terminal, start the frontend:
   ```bash
   cd frontend
   npm start
   ```

3. Open your browser and navigate to `http://localhost:3000`

## Features

- Modern Material-UI based interface
- Real-time chat with AI
- Responsive design
- Loading states and error handling
- Auto-scrolling chat window 
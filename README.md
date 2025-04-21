# Smart-chat-bot
# Chat Assistant

A real-time demo chat application built with React, Express, and WebSocket that lets you interact with an AI assistant. Features include:

- Real-time messaging with AI
- Message search functionality
- Chat export options (HTML, Text, JSON)
- Clean and responsive UI
- Message history persistence

## Getting Started

1. Clone this repl
2. Run `npm install` to install dependencies
3. Click the Run button to start the development server
4. Open the app in your browser

## Tech Stack

- Frontend: React + TypeScript + Tailwind CSS
- Backend: Express + WebSocket
- Database: SQLite with Drizzle ORM
- AI: OpenRouter API integration

## Additional Notes

- The ChatBot currently can not recall previous prompts and give an answer based off of those, demonstrated in the video.
- There's an a slightly issue with the outputs giving '0' at the end of the message, which is due to the message ID label.
- It uses DeepSeek: DeepSeek V3 0324 for it's AI.

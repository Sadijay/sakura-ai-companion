#  Sakura - Local Ai Companion

Sakura is a privacy-focused desktop AI companion powered by
local LLMs through Ollama. 

It provides an always-available desktop assistant capable of
chatting with the user, maintaining conversation history and
controlling desktop applications in windows OS.

## ✨ Features

- 🤖 Local AI inference with Ollama
- 💬 Streaming AI responses
- 🧠 Persistent conversation history
- 🌸 Animated desktop companion interface
- 📌 System tray integration
- 🚀 Optional launch on startup
- 🔒 Runs locally without requiring a cloud AI API

## 🛠 Built With

- React
- TypeScript
- Electron
- Ollama
- Vite

## 📸 Screenshots

<img width="320" height="600" alt="image" src="https://github.com/user-attachments/assets/a40e51d6-6f16-4704-9c88-472556fa1db9" />

## 🚀 Installation

1. Install Node.js
2. Install Ollama
3. Pull the Phi-3 model
4. Clone this repository
5. Run npm install
6. Run npm run dev

## 🏗 Architecture

React UI
   ↓
Electron IPC
   ↓
Node/Electron backend
   ↓
Ollama
   ↓
Phi-3 LLM

## 🔮 Roadmap

- Voice input
- Voice responses
- Improved application automation
- Multiple LLM selection
- Better memory
- Cross-platform support

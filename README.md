# CHATBOT - Web-Based Chatbot Project

![Project Preview](assets/screenshot.png)

## Overview
A web-based chatbot built with HTML, CSS, and JavaScript that provides an interactive chat interface in the browser.

## Features
- 💬 Interactive web interface
- 🧠 JavaScript conversation logic
- 🎨 CSS animations and responsive design
- 💾 Optional local storage for conversation history
- 🚀 Easy deployment (static files)

## Installation

### Quick Start
```bash
git clone https://github.com/priyanshusingh017/CHATBOT.git
cd CHATBOT
```

# Running Locally
Open `index.html` directly in your browser

Or use a local server:
```bash
npx serve
# or
python -m http.server 8000
```

## Project Structure

```plaintext
CHATBOT/
├── index.html         # Main HTML file
├── style.css          # CSS styles
├── script.js          # Chatbot logic
├── assets/            # Media files
│   ├── bot-icon.png   # Chatbot icon
│   └── screenshot.png # Project screenshot
└── README.md          # Documentation
```

## Usage

Add custom responses by editing the JavaScript file:

```javascript
// script.js - Response configuration
const botResponses = {
  "hello": "Hi there! How can I help you today?",
  "goodbye": "See you later! Come back anytime.",
  "help": "I can answer questions about this project."
};
```

## Customization

### Modify Responses
```javascript
// Add or update responses in script.js
botResponses["new question"] = "Custom response text";
botResponses["existing question"] = "Updated response text";
```

## UI Customization

### Message Styling
```css
/* style.css - Chat message styling */
.user-message {
  background-color: #4CAF50;       /* Green background for user */
  color: white;
  border-radius: 8px;
  padding: 8px 12px;
  margin: 8px 0;
  max-width: 80%;
  align-self: flex-end;
}

.bot-message {
  background-color: #2196F3;       /* Blue background for bot */
  color: white;
  border-radius: 8px;
  padding: 8px 12px;
  margin: 8px 0;
  max-width: 80%;
  align-self: flex-start;
}

/* Chat container styling */
.chat-container {
  max-width: 800px;
  margin: 0 auto;
  padding: 20px;
  height: 100vh;
  display: flex;
  flex-direction: column;
  background-color: #f5f5f5;
}

/* Input area styling */
.chat-input {
  padding: 10px;
  position: fixed;
  bottom: 0;
  width: 100%;
  max-width: 800px;
  background: white;
}
```

## Development Setup
```bash
# 1. Clone the repository
git clone https://github.com/priyanshusingh017/CHATBOT.git
cd CHATBOT

# 2. Install live-server (if not installed)
npm install -g live-server

# 3. Start development server with options:
live-server \
  --port=3000 \
  --open=index.html \
  --watch=style.css,script.js
```

## How to Contribute

1. **Fork** the repo on GitHub
2. **Clone** your fork:
   ```bash
   git clone https://github.com/YOUR-USERNAME/CHATBOT.git
   cd CHATBOT
3. Create branch:
   ```bash
   git checkout -b feat/your-feature
4. Make changes and commit::
   ```bash
   git add .
   git commit -m "feat: add new feature"

5. Push and create a Pull Request

## 📜 License 

**MIT License**  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

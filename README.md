# AI Trip Planner Bot

An intelligent conversational agent built with OpenAI's AGENTS SDK that helps users plan their trips through natural language interaction.

## 🌟 Features

- Interactive conversation-based trip planning
- Conversation history management
- Context-aware responses
- Command support ('exit' and 'clear')
- Asynchronous processing
- Conversation logging system

## 🛠️ Technologies Used

- Python 3.x
- GEMINI API KEY
- Agents SDK
- AsyncIO

## 📋 Prerequisites

Before running this project, make sure you have:

- Python 3.x installed
- GEMINI API KEY
- Required Python packages installed

## ⚙️ Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/ai-trip-planner.git
cd ai-trip-planner
```

2. Create and activate a virtual environment:
```bash
python -m venv .venv
# Windows
.venv\Scripts\activate
```

3. Install required packages:
```bash
pip install -r requirements.txt
```

4. Set up your environment variables:
```bash
# Windows
set GEMINI_API_KEY=your_api_key_here
```

## 🚀 Usage

Run the main script:
```bash
python main.py
```

### Available Commands:
- Type your travel-related queries naturally
- Type 'exit' to end the conversation
- Type 'clear' to start a fresh conversation

## 📁 Project Structure

```
ai-trip-planner/
├── main.py
├── Agents/
│   └── Agents.py
├── History/
│   └── History.py
├── LLm_Setup/
│   └── llm.py
├── conversation_logs/
└── README.md
```

## 💡 Example Interaction

```
Trip Planner Bot: Hello! I can help you plan your trip. Type 'exit' to end the conversation or 'clear' to start fresh.

Enter Query: I want to plan a trip to Paris
[Bot responds with Paris travel suggestions]

Enter Query: What are some must-visit places?
[Bot provides list of attractions]

Enter Query: exit
Trip Planner Bot: Goodbye!
```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👥 Authors

- Muhammad Younus 

## 🙏 Acknowledgments

- GOOGLE GEMINI FOR PROVIDING API
- Agents SDK contributors
- All contributors to this project

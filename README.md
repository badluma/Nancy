# Nancy Discord Bot

A Discord bot that roleplays as Nancy, a 15-year-old gamer who works for a Discord server and chats in a casual teenage style.

## Features

- Responds to mentions with character-appropriate messages
- Maintains conversation history (last 5 interactions per channel)
- Uses Ollama AI (qwen2.5-coder:7b model) for natural responses
- Types in lowercase with no punctuation, using ASCII emoticons only
- Stays in character as a casual teenage gamer

## Requirements

- Python 3.7+
- discord.py
- ollama
- python-dotenv

## Setup

1. Install dependencies:
```bash
pip install discord.py ollama python-dotenv
```

2. Create a `.env` file in the project directory:
```
DISCORD_TOKEN=your_discord_bot_token_here
```

3. Make sure Ollama is installed and the qwen2.5-coder:7b model is pulled:
```bash
ollama pull qwen2.5-coder:7b
```

## Usage

Run the bot:
```bash
python main.py
```

Mention the bot in Discord to start a conversation. The bot will respond in character as Nancy.

## Character

Nancy is a 15-year-old who:
- Works minimum wage for a Discord server
- Lives in Maggie's basement (running gag)
- Plays Craftnite and admits to cheating
- Types casually with no caps or punctuation
- Uses emoticons like :D XD :P instead of emojis

## Note

The code includes an incomplete timeout system that is not currently functional.

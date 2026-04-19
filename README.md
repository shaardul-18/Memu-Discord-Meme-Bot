# Discord Meme Bot

A Discord bot built using Python and the `discord.py` library.
This project is based on the Codédex tutorial and demonstrates how to create a simple, functional bot that responds to user commands and events.

---

## Features

* Responds to custom commands (e.g., `!hello`, `!ping`)
* Handles Discord events like bot startup and messages
* Easy to modify and extend
* Beginner-friendly project structure

---

## Tech Stack

* Python 3.10+
* discord.py

---

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/discord-bot.git
cd discord-bot
```

### 2. Install Dependencies

```bash
pip install discord.py
```

---

## Setup Instructions

1. Go to the Discord Developer Portal
2. Create a new application
3. Navigate to the **Bot** section
4. Click **Add Bot**
5. Copy your bot token

⚠️ Do not share your bot token publicly.

---

## Configuration

Open your `bot.py` file and replace the token:

```python
TOKEN = "YOUR_BOT_TOKEN"
```

For better security, use environment variables:

```python
import os
TOKEN = os.getenv("DISCORD_TOKEN")
```

---

## Running the Bot

```bash
python bot.py
```

If successful, you should see:

```
Bot is ready!
```

---

## Example Commands

| Command  | Description              |
| -------- | ------------------------ |
| `!hello` | Replies with a greeting  |
| `!ping`  | Returns bot latency      |
| `!help`  | Lists available commands |

---

## Project Structure

```
discord-bot/
│
├── bot.py
├── README.md
```

---

## Future Improvements

* Add slash commands (`/commands`)
* Add moderation features (kick, ban, mute)
* Store data using a database (SQLite / MongoDB)
* Deploy bot to cloud (AWS, Render, etc.)

---

## Acknowledgements

* Codédex Discord Bot Tutorial
* discord.py Documentation

---


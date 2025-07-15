# 🌟 Telegram Horoscope Bot

A simple Python-based Telegram bot that fetches daily horoscopes using a public API. Built using the `pyTelegramBotAPI` library and easily deployable to platforms like Render or Railway.

---

## 📦 Features

- Responds to `/start` and `/hello` with a welcome message.
- Handles `/horoscope` command:
  - Asks for zodiac sign.
  - Asks for the day (`TODAY`, `TOMORROW`, or `YESTERDAY`).
  - Replies with a detailed daily horoscope fetched from a public API.
- Supports multiple users at once (with deployment).
- Securely manages the bot token using `.env` file.

---

## 🚀 Getting Started

### 🔧 Prerequisites

- Python 3.7+
- Telegram account
- A bot token from [@BotFather](https://t.me/BotFather)

### 🛠️ Installation

1. **Clone the repo**

```bash
git clone https://github.com/your-username/telegram-horoscope-bot.git
cd telegram-horoscope-bot

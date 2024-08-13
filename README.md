# Daily Horoscope Telegram Bot

This is a Python-based Telegram bot that provides daily horoscopes for different zodiac signs. Users can interact with the bot to get their horoscope for today, tomorrow, yesterday, or any specific date.

## Features

- **Welcome Message**: The bot greets users with a friendly message when they start a conversation.
- **Horoscope Request**: Users can request a daily horoscope by specifying their zodiac sign and the desired date.
- **Dynamic Date Input**: Users can choose to get the horoscope for today, tomorrow, yesterday, or enter a specific date in `YYYY-MM-DD` format.
- **Echo Functionality**: The bot echoes any message sent by the user that doesn't match the predefined commands.

## Requirements

- Python 3.x
- `telebot` library (PyTelegramBotAPI)
- `requests` library

## Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/horoscope-telegram-bot.git
    cd horoscope-telegram-bot
    ```

2. Install the required libraries:
    ```bash
    pip install pyTelegramBotAPI requests
    ```

3. Set your bot token in the `BOT_TOKEN` variable in the script:
    ```python
    BOT_TOKEN = "your_telegram_bot_token_here"
    ```

4. Run the bot:
    ```bash
    python bot.py
    ```

## Usage

1. Start the bot by sending the `/start` or `/hello` command.
2. Request your horoscope by sending the `/horoscope` command.
3. Follow the bot's prompts to select your zodiac sign and the desired date.

## Code Overview

- **bot.py**: Main script that contains the bot logic. Handles user interaction and requests horoscopes.
- **utils.py**: Utility script that defines the `get_daily_horoscope` function, which fetches horoscope data from an external API.

## API

The bot uses the [Horoscope API](https://horoscope-app-api.vercel.app/) to fetch daily horoscope data.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.



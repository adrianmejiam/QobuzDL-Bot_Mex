# QobuzDL-Bot
This bot allows you to search for and download music from Qobuz directly in Telegram.

## Requirements
- Python 3.8+
- Qobuz subscription
- Telegram bot token

## Installation

1. Clone or download this project.
2. Set dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Create a `.env` file based on `.env.example` and fill in your details:
   ```env
   TELEGRAM_BOT_TOKEN=your_token
   QOBUZ_EMAIL=your_email
   QOBUZ_PASSWORD=your_password
   DOWNLOAD_PATH=./downloads
   DEFAULT_QUALITY=6
   ```

## Sound quality (DEFAULT_QUALITY)
- `5`: MP3 320kbps
- `6`: FLAC 16-bit / 44.1kHz (CD Quality)
- `7`: FLAC 24-bit / up to 96kHz
- `27`: FLAC 24-bit / above 96kHz

## Usage
Start:
```bash
python main.py
```
In Telegram, send the bot the name of the album/track or a direct link to Qobuz.

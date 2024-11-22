# Discord Bot

## Overview
The **Discord Bot** is a simple Python-based bot designed to enhance user interaction within Discord servers by allowing users to fetch and share random memes. This project showcases the integration of the Discord API with external data sources.

## Features
- **Meme Command**: Users can type `$meme` to receive a random meme from an external API.
- **User-Friendly Interaction**: Simple commands make it easy for users to engage with the bot.
- **Secure Token Management**: Utilizes environment variables to keep sensitive information, like the Discord token, safe.

## Technologies Used
- **Python**: The programming language used for developing the bot.
- **discord.py**: A library that simplifies interactions with the Discord API.
- **Requests**: A library for making HTTP requests to fetch memes.
- **dotenv**: A package for managing environment variables securely.

## Installation Instructions
To run the Discord bot locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/freddyfavour/discord-bot.git
   ```

2. **Navigate to the Project Directory**:
   ```bash
   cd discord-bot
   ```

3. **Create a `requirements.txt` File**:
   Create a file named `requirements.txt` in your project directory and add these dependencies:
   ```plaintext
   discord.py
   requests
   python-dotenv
   ```

4. **Install Dependencies**:
   Install the required packages using pip:
   ```bash
   pip install -r requirements.txt
   ```

5. **Create a `.env` File**:
   Add your Discord bot token to a `.env` file in the project directory:
   ```plaintext
   DISCORD_TOKEN=your_discord_bot_token_here
   ```

6. **Run the Bot**:
   ```bash
   python bot.py
   ```

## Usage Instructions
- Invite your bot to your Discord server using the OAuth2 URL generated on the Discord Developer Portal.
- Type `$meme` in any channel where the bot has access, and it will respond with a random meme.

## Future Improvements
- Add more commands for different types of content (e.g., jokes, quotes).
- Implement user authentication and role-based access for certain commands.
- Enhance error handling and logging for better debugging.

## Acknowledgments
Special thanks to Codedex and the creators of `discord.py` for providing an excellent library for building Discord bots and to the community for their support.

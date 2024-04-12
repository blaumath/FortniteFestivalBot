# Fortnite Festival Bot

This is a Discord bot for managing Fortnite events. It can create text channels, manage commands, handle events, and post music tracks.

## Installation

1. Clone this repository: `git clone https://github.com/yourusername/fortnite-festival-bot.git`
2. Navigate to the project directory: `cd fortnite-festival-bot`
3. Install the dependencies: `npm install`
4. Rename `config.example.json` to `config.json` and fill in your details. See the Configuration section below for more details.
5. Start the bot: `node src/index.js`

## Configuration

In the `config.json` file, you need to provide the following information:

- `clientId`: This is your bot's client ID. You can get this from your bot's page on the [Discord Developer Portal](https://discord.com/developers/applications).
- `guildId`: This is the ID of the server where the bot will be used. You can get this by right-clicking the server in Discord and selecting "Copy ID".
- `token`: This is your bot's token. You can get this from your bot's page on the [Discord Developer Portal](https://discord.com/developers/applications). Keep this token safe and do not share it with anyone.
- `channelId`: This is the ID of the channel where the bot will post music tracks. You can get this by right-clicking the channel in Discord and selecting "Copy ID".

## Features
- Music search: The bot has a search command to find music tracks.
- Music posting: By defining a channel ID, the bot will post all the music tracks in that channel.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.
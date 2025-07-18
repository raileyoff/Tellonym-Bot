# NextGen Discord Bot

A feature-rich Discord bot for the NextGen community, built with Discord.js v14 and ES modules.

## 🚀 Features

- **Moderation Commands**: Keep your server safe and organized
- **Utility Commands**: Helpful tools for server management
- **Event System**: Fully customizable event handlers
- **Clean Architecture**: Organized codebase for easy maintenance
- **ES Modules**: Modern JavaScript with ES modules

## 🛠️ Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/nextgen-bot.git
   cd nextgen-bot
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Configure the bot**
   - Open `src/config.js`
   - Update the `token` with your Discord bot token
   - Configure other settings as needed

4. **Start the bot**
   ```bash
   # Development
   npm run dev
   
   # Production
   npm start
   ```

## ⚙️ Configuration

Edit `src/config.js` to configure your bot:

```javascript
export default {
  // Bot token (get this from Discord Developer Portal)
  token: 'YOUR_BOT_TOKEN_HERE',
  
  // Bot prefix for commands
  prefix: '!',
  
  // Bot status
  status: {
    type: 'WATCHING', // PLAYING, WATCHING, LISTENING, STREAMING
    message: 'NextGen Community 👨‍💻',
  },
  
  // ... other configurations
};
```

## 📂 Project Structure

```
nextgen-bot/
├── src/
│   ├── commands/         # Command files
│   │   ├── moderation/   # Moderation commands
│   │   └── utility/      # Utility commands
│   ├── events/           # Event handlers
│   ├── utils/            # Utility functions
│   ├── config.js         # Bot configuration
│   └── index.js          # Bot entry point
├── .env                  # Environment variables
├── package.json          # Project dependencies
└── README.md             # This file
```

## 🤖 Available Commands

### Moderation
- `!clear <amount>` - Clear a specified number of messages

### Utility
- `!ping` - Check the bot's latency
- `!help [command]` - Show all commands or info about a specific command

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
#   T e l l o n y m - B o t 
 
 #   T e l l o n y m - B o t 
 
 

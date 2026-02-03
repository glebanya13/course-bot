# 🔥 Course Bot Telegram
The SuetaWBBot is a comprehensive bot application designed to interact with users through a messaging platform, providing a range of functionalities and services. The bot is built using a modular architecture, with separate modules for handling messages, commands, and callbacks, as well as services for managing user data and administrative tasks. The project aims to provide a flexible and customizable bot solution that can be easily integrated with various messaging platforms.

## 🚀 Features
- **Modular Architecture**: The bot is built using a modular architecture, with separate modules for handling messages, commands, and callbacks.
- **User Management**: The bot includes a user service for managing user data, including adding users, retrieving user lists, and managing user states and payment information.
- **Administrative Tasks**: The bot includes an admin service for managing administrative tasks, including displaying admin menus, handling admin commands, and managing payments and broadcasts.
- **Callback Handling**: The bot includes a callback handler for handling callback queries from users, determining the course of action based on the callback data.
- **Logging**: The bot includes a custom logging utility for logging messages at different levels of severity.

## 🛠️ Tech Stack
- **Node.js**: The bot is built using Node.js as the runtime environment.
- **Telegram Bot API**: The bot uses the Telegram Bot API for interacting with the Telegram messaging platform.
- **better-sqlite3**: The bot uses the better-sqlite3 library for interacting with the SQLite database.
- **dotenv**: The bot uses the dotenv library for loading environment variables.
- **node-telegram-bot-api**: The bot uses the node-telegram-bot-api library for interacting with the Telegram Bot API.

## 📦 Installation
To install the bot, follow these steps:
1. Clone the repository using `git clone`.
2. Install the dependencies using `npm install`.
3. Create a `.env` file and add the required environment variables, including the bot token, channel ID, contact username, payment information, and admin chat ID.
4. Run the bot using `node src/index.js`.

## 💻 Usage
To use the bot, follow these steps:
1. Start the bot by running `node src/index.js`.
2. Interact with the bot by sending messages or commands.
3. Use the `/start` command to begin the conversation.
4. Use the `/help` command to view the available commands.

## 📂 Project Structure
```markdown
src
├── index.js
├── bot.js
├── database
│   ├── database.js
│   └── schema.sql
├── handlers
│   ├── command.handler.js
│   └── callback.handler.js
├── services
│   ├── admin.service.js
│   └── user.service.js
├── utils
│   └── logger.js
├── config
│   └── bot.config.js
└── keyboards
    └── keyboards.js
```

## 🤝 Contributing
To contribute to the project, follow these steps:
1. Fork the repository using `git fork`.
2. Create a new branch using `git branch`.
3. Make changes to the code and commit them using `git commit`.
4. Push the changes to the remote repository using `git push`.
5. Create a pull request to merge the changes into the main branch.

## 📝 License
The project is licensed under the MIT License.

## 📬 Contact
For any questions or concerns, please contact us at [glebanya.com@gmail.com](mailto:glebanya.com@gmail.com).

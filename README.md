# QuickDiscord

A simple and efficient Discord bot generator that helps you set up a bot with database support, cogs, and environment configurations in seconds! 🚀

## ✨ Features

- 🔧 **Quick Setup** – Generate a fully functional Discord bot project effortlessly.
- 📂 **Modular Cogs Support** – Choose to use cogs for a structured and scalable bot.
- 🛢️ **Database Integration** – Supports SQLite, PostgreSQL, and MongoDB.
- ⚙️ **Configurable Environment** – Use either `config.py` or `.env` for storing credentials.
- 📦 **Automated Dependency Installation** – Installs required packages automatically.

---

## 📌 Installation

### Prerequisites
Make sure you have **Python 3.8+** installed.

```bash
python --version
```

### Install QuickDiscord

```bash
pip install quickdiscord
```

---

## 🚀 Usage

To generate a new bot project, run:

```bash
python -m quickdiscord
```

You'll be prompted with a series of questions to customize your bot:

- **Programming Language** (Currently only Python is supported)
- **Configuration Method** (`config.py` or `.env`)
- **Use Cogs?** (Modular command files)
- **Database Type** (None, SQLite, PostgreSQL, MongoDB)

After answering the prompts, QuickDiscord will generate the project structure and install dependencies automatically. 🎉

---

## 📁 Project Structure

```
📦 YourBotProject
├── 📂 cogs/             # Stores command files (if cogs are enabled)
│   ├── __init__.py
│   ├── example.py       # Example cog
├── 📜 main.py           # Main bot file
├── 📜 config.py         # Stores bot token and prefix (if config.py is chosen)
├── 📜 .env              # Stores bot token and prefix (if .env is chosen)
├── 📜 database.py       # Database setup file (if a database is selected)
└── 📜 requirements.txt  # Installed dependencies
```

---

## 🔧 Available Commands

Once your bot is running, you can use these basic commands:

| Command  | Description        |
|----------|--------------------|
| `!hello` | Responds with "Hello!" |
| More...  | Add your own commands! |

---

## 🛠️ Supported Databases

QuickDiscord allows you to choose a database during setup:

- **SQLite** (Default, lightweight, file-based)
- **PostgreSQL** (Enterprise-level, requires `psycopg2`)
- **MongoDB** (NoSQL database, requires `pymongo`)

---

## 💡 Example

After generating your bot, navigate to your project folder and run:

```bash
python main.py
```

Your bot should now be running! 🎉

---

## 🎯 Contributing

We welcome contributions! Feel free to submit a pull request or open an issue.

---

## 📜 License

QuickDiscord is open-source and licensed under the **MIT License**.

---

## 📬 Need Help?

- 📖 [Official Discord.py Documentation](https://discordpy.readthedocs.io/en/stable/)
- 🛠️ Open an issue if you run into problems!

Happy coding! 🎩✨
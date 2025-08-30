### Health Bot

A lightweight Discord bot that offers diet and exercise suggestions based on the foods users eat. Built using Python.

### What It Does

- Parses food data from CSV files (e.g., FOOD NAME.csv, NUTRIENT AMOUNT.csv)

- Interacts with users on Discord via bot commands (bot.py, main.py)

- Provides recommendations for nutrition and exercise (responses.py)

- Tracks user data using CSV-based storage (user.csv, users.csv)

### Quick Start

Clone the repository
```
git clone https://github.com/JoshuaZhang7567/health-bot.git
cd health-bot
```

### Install dependencies

(Assuming discord.py is used; adapt as needed)
```
pip install discord.py pandas
```

### Run the bot
```
python bot.py
```

Make sure your Discord bot token is configured as required (e.g., environment variable, config file, etc.).

### Skills Highlighted

- CSV-based data parsing and manipulation

- Discord bot development with Python

- Modular code structure (parse.py, responses.py, etc.)

- Basic user tracking and recommendation logic

### Possible Enhancements

- Add configuration support (e.g., JSON or .env for secrets and settings)

- Use a database (like SQLite) for user data

- Expand recommendations (e.g., macronutrients, workout routines)

- Add command help or richer user interactions

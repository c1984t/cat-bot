se

Discord Cat Bot Source Code

# Development

x

## Prerequisites

- Python 3
- Git (optional)
- PostgreSQL (optional)

## Instructions

1. Clone the repository. You can use green "Code" button at the top or a git command:

   `git clone https://github.com/milenakos/cat-bot.git`

2. Install requirements:

   `pip install -r requirements.txt`

   If you are running a Gateway Proxy, do `pip install -r requirements-gw.txt` instead. This uses a custom fork which contacts `localhost:7878` instead, removes ratelimits and heartbeats.

3. You will need to add all emojis you want to Discord's App Emoji in the Dev Portal.

   If they aren't found there, they will be replaced with a placeholder.

   All emojis can be downloaded [here](https://github.com/staring-cat/emojis/releases/latest/download/emojis.zip).

4. Go inside of the `config.py` file and configure everything for your liking.

5. Run the bot with `python bot.py`

6. Done!

# License

Cat Bot is licensed under GNU Affero General Public License v3.0 license. View `LICENSE` for more information.

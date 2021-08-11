# Getting Started

## User Installation

Most Discord Bots are accessed through an invite. Currently as Rin is in alpha stages, and I don't have anywhere to host it, it is not available for invites. It will be available on top.gg and invites will also be through top.gg

## Development Installation

Getting all the dependencies is easy enough. Here's the list that is needed:

- Git
- Python 3.6 and above (Made in 3.9.6)
- pip 
- Discord.py
- Python-dotenv
- Cog Watch 

All of the dependencies are listed within the requirements.txt file in the root directory.

## Running the Discord Bot

A discord bot is normally online when the bot file (in this case, the file is `rinbot.py` and housed within the Bot directory) is online. The token must be accessed in order to work, and this token is stored within a .env file. The only way to run it for development is to use the official [Rin Docker Image](https://hub.docker.com/r/no767/rin). Pull down the image, and run that discord bot. If the .env file is missing, that means there is no way to get the bot online for development. The repo only is meant to hold the source code itself. 
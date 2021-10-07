<h1 align="center">
    <br>
    SPC Discord BOT
    <br>
</h1>

<p align="center">
  <a href="https://discord.gg/JH2Zdzu">
    <img src="https://discord.com/api/guilds/535168332542771230/widget.png?style=shield" alt="Discord Server">
  </a>
  <a href="https://www.python.org/downloads/">
    <img alt="Python Version" src="https://img.shields.io/badge/python-3.8+-blue.svg">
  </a>
  <a href="https://pypi.org/project/openpyxl/">
     <img src="https://img.shields.io/badge/gspread-v4-blue.svg">
  </a>
  <a href="https://docs.gspread.org/en/v4.0.1/">
     <img src="https://img.shields.io/badge/openpyxl-v3-blue.svg">
  </a>
  <a href="https://github.com/Rapptz/discord.py/">
     <img src="https://img.shields.io/badge/discord-py-blue.svg" alt="discord.py">
  </a>
</p>

<p align="center">
  <a href="#overview">Overview</a>
  •
  <a href="#installation">Installation</a>
  •
  <a href="#run-command">Run Command</a>
</p>

# Overview

SPC BOT is a discord bot I made to automate verification process for the campus placement in RVCE.

It's main job is to use the data present in google spreadsheet and verify it with the data of responses from a downloaded .xlsx file.

To invite the bot to your server use this <a href = "https://discord.com/api/oauth2/authorize?client_id=891279485519937557&permissions=534992387152&scope=bot">Invitation Link</a>.

The prefix for this bot is **-**. Use command **-help** to explore different commands.

# Installation

The recommended python version for this bot is 3.8+. To install the packages used in this project, you can use the following commands in the command prompt.

```
pip install discord.py
pip install gspread
pip install oauth2client
pip install openpyxl
pip install os
pip install requests
pip install dotenv
```

# Run Command
```
python spcbot.py
```

After the bot is online, you can use the -help command to get started.
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

<!-- To invite the bot to your server use this <a href = "https://discord.com/api/oauth2/authorize?client_id=891279485519937557&permissions=534992387152&scope=bot">Invitation Link</a>. -->

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
You need to create a project in the <a href = "https://console.cloud.google.com/">Google's Developers Console</a>.

After creating the project go to the marketplace and install the following apis:
- <a href = "https://console.developers.google.com/apis/library/sheets.googleapis.com/">Google Sheets API</a>
- <a href = "https://console.developers.google.com/apis/library/drive.googleapis.com/">Google Drive API</a>

To access the google spreadsheet you want to work with you will have to create a <a href = "https://console.cloud.google.com/iam-admin/serviceaccounts">Google Service Account</a>. Give editor access to this account in the spreadsheet you are working on. Download the service account API key in JSON format and upload it in your working directory.

To make your own bot go to <a href = "https://discord.com/developers/applications">Discord's Developers Portal</a> and create an application. Go to OAuth2 and select bot then enable all the text permissions, you will get a link and this will be the invitation link for your bot. Copy the token for your bot and create a .env file in the working directory. In the .env file type TOKEN=yourcopiedtoken.

# Run Command
```
python spcbot.py
```

After the bot is online, you can use the -help command to get started.


# ðŸ”¥ KAPIL SPAM BOT

[![Telegram Channel](https://img.shields.io/badge/Update%20Channel-KomalBotsNetwork-blue?style=flat&logo=telegram)](https://t.me/KomalBotsNetwork)  
[![Support Group](https://img.shields.io/badge/Support%20Group-KomalMusicRobotSupport-green?style=flat&logo=telegram)](https://t.me/KomalMusicRobotSupport)

<p align="center">
  <img src="https://files.catbox.moe/lg4old.jpg" alt="Kapil Spam Bot Banner" width="500px">
</p>

> A powerful **Telethon-based Spam Bot** with multi-user control  
> Built with â¤ï¸ by **Kapil Yadav**

---

## âœ¨ Features

- ðŸš€ Multi-user support  
- ðŸ›¡ï¸ Smart sudo system  
- âš¡ Blazing fast performance  
- ðŸ”Œ Telethon-powered  
- ðŸ˜Ž User-friendly interface

---

## ðŸš€ Deployment

### â˜ï¸ Heroku Deployment

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/RockMusicBot/RockSpam.git)

---

### ðŸ’» VPS Deployment Guide

#### ðŸ”§ Prerequisites

```bash
sudo apt update && sudo apt upgrade -y
sudo apt install python3 python3-pip git screen -y
```

#### ðŸ“¥ Clone the Repository

```bash
git clone https://github.com/RockMusicBot/RockSpam.git
cd RockSpam
```

#### ðŸ“¦ Install Requirements

```bash
pip3 install -U pip
pip3 install -r requirements.txt
```

#### âš™ï¸ Configure Your Bot

Set the following environment variables:
- `API_ID`, `API_HASH` from [my.telegram.org](https://my.telegram.org)
- `BOT_TOKEN` from [@BotFather](https://t.me/BotFather)
- `SUDO_USERS` (Telegram user IDs)
- `OWNER_ID`, `LOG_CHANNEL_ID`, etc.

Create a `.env` or use `os.environ` in your script to load them.

#### ðŸš€ Start the Bot

```bash
screen
python3 main.py
```

To detach screen: `Ctrl+A` then `D`  
To resume: `screen -ls` and then `screen -r <id>`

---

<p align="center">
  <img src="https://img.shields.io/badge/Made%20with%20%E2%9D%A4%EF%B8%8F%20by-Kapil%20Yadav-red?style=for-the-badge" alt="Made with love">
</p>

---

<p align="center">
<b>ðŸ’¬ Stay connected with Komal Bots Network for updates and support!</b>
</p>

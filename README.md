# camTGalert
[![GitHub issues](https://img.shields.io/github/issues/okno/camtgalert.svg)](https://github.com/okno/camtgalert/issues) [![GitHub stars](https://img.shields.io/github/stars/okno/camtgalert.svg)](https://github.com/okno/camtgalert/stargazers) [![Twitter](https://img.shields.io/twitter/url/https/github.com/okno/camtgalert.svg?style=social)](https://twitter.com/intent/tweet?text=Wow:&url=https%3A%2F%2Fgithub.com%2Fokno%2Fcamtgalert)
![GitHub license](https://img.shields.io/github/license/okno/camtgalert.svg)

## Descrizione
**camTGalert** is a Linux cli, GUI &amp; Daemon/Service application that captures images and videos from your webcam, detects motion and sends notifications via Telegram written by Pawel 'okno' Zorzan Urban.

## Main functions are
- `Capture Images`
- `Compare from last`
- `Detect Motion`
- `Highlights Motion Area`
- `Video Record`
- `Daemon Mode`
- `Graphic User Interface`
- `Live Preview`
- `Easy configuration`
- `Configuration Backup`
- `Telegram BOT Connection`
- `Multi Thread`
- `Logging`

## Installation

### Dependencies
These are the main dependencies:
- python-telegram-bot
- opencv-python
- opencv-python-headless
- v4l-utils

To install the depedencies run:
```bash
pip3 install python-telegram-bot opencv-python opencv-python-headless
```
### Core 
```bash
git clone ...
```
### Paths, Logs, Files: 
File | Description
------------- | -------------
/opt/camtgalert/ | Default Working camTGalert Folder
/opt/camtgalert/bot.config | Default Configuration File 
/opt/camtgalert/camtgalert.py | Main Application File
/opt/camtgalert/telegram_functions.py | BOT Functions 
/opt/camtgalert/telegrambotcam.service | Systemd Service Registration file
/opt/camtgalert/video_img | Default Video and Image Folder
/opt/camtgalert/backups | Default Configuraton Backup Folder

### Configuration Parameters 
Variabile | Description | Type
------------- | ------------- | -------------
time_recording | tempo di registrazione in secondi.
output_folder | cartella di destinazione per i file acquisiti.
max_storage | dimensione massima dello storage in gigabyte.
log_file | percorso del file di log.
bot_token | token del bot Telegram.
group_id | ID del gruppo Telegram per le notifiche.

## TODO!
- Optimize Threads and Loops 
- Complete English Translate
- Complete Italian Translate

### Contribution

You can contribute in following ways:

   - Report bugs
   - Give suggestions to make it better
   - Fix issues & submit a pull request

### Credits 
 `Pawel Zorzan Urban` alias okno 
Contact | URL
------------- | -------------
website | https://pawelzorzan.com 
linkedin | https://www.linkedin.com/in/pawelzorzan/
Do you want to have a conversation in private? 
Hit me up on my [twitter](https://twitter.com/pawelzorzan)

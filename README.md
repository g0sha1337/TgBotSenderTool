# TgBotSenderTool
Tool for sending advertising or any other notifications to the id-database in your telegram bot

## What was this utility written for?
The main need for this application is that not all backend telegram bots support effective sending alerts to users. This software allows you to make a sending alerts to your bot user base in a format convenient for you.

## What is needed to launch?

### 1) Install requirements.txt
```
pip install -r requirements.txt
```
### 2) Put token of your bot in config.py
```
TelegramBotToken = 'Your_secret_tg_token' #from @BotFather
```
### 3) Extract telegram id from your database and fill it in database txt file
### 4) Prepare your text message file, image and inline buttons

# Example of usage

```
python sender.py --database ids.txt --text msg.txt --image image.png --inline inline.txt
```

Enjoy! 

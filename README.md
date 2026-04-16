Programming Joke Email Sender
Python script that fetches programming jokes from JokeAPI and sends them via email.
Features

-Fetches jokes from JokeAPI
-Sends via Gmail SMTP with TLS
-Secure credential management (external JSON)
-Comprehensive logging
-Specific exception handling

Setup

Install dependencies:

bashpip install requests

Create credentials file (Python CS/creds_email.json):

json{
    "email": "your-email@gmail.com",
    "password": "your-gmail-app-password"
}
Note: Use a Gmail App Password, not your regular password. Never commit this file.
Usage
bashpython joke_email_sender.py
Configuration

Recipient: Change recipient variable in the script (line 19)
Log file: email_send.log
API: JokeAPI Programming category with content filters

License
MIT


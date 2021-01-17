# Twitch-PyBot

<img src="https://img.shields.io/badge/Python-100%25-green.svg">

This is a simple Python chatbot for twitch using IRC.

### Setup

```
git clone https://github.com/aamit2267/Twitch-PyBot.git
cd ./Twitch-PyBot/
pip install -r requirements.txt
```


## Usage
To run the chatbot, you will need to provide an OAuth access token with the chat_login scope. 
You can reference an authentication sample to accomplish this, or simply use the [Twitch Chat OAuth Password Generator](http://twitchapps.com/tmi/).

```sh
$ python twitch.py <username> <client_id> <token> <channel>
```
* Username - The username of the chatbot
* Client ID - Your registered application's Client ID to allow API calls by the bot
* Token - Your OAuth Token
* Channel - The channel your bot will connect to

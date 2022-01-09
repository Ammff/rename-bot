# TG-RENAMER-BOT
## Rename Bot - Clone of  [Renamer⚡](https://t.me/renamer_Ns_bot)
---

An Open Source Rename Telegram RoBot

**My Feature**:

👉 Rename any Telegram Files with Custom Thumbnail Support and upload as file or video

### Installation

#### The Easy Way

**Watch infotel Video for knowing how to Create yoir own Bot** - 👉 https://youtu.be/yYHrSnuYXpA
###Deploy on Railway
[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template?template=https%3A%2F%2Fgithub.com%2FAmmff%2Frename-bot%2Fblob%2Fmaster%2FProcfile&envs=API_HASH%2CAPP_ID%2CAUTH_USERS%2CBANNED_USERS%2CCHAT_BASE_TOKEN%2CCHUNK_SIZE%2CTG_BOT_TOKEN%2CUSER_NAME%2CWEBHOOK&optionalEnvs=WEBHOOK&API_HASHDesc=Get+this+value+from+https%3A%2F%2Fmy.telegram.org&APP_IDDesc=Get+this+value+from+https%3A%2F%2Fmy.telegram.org&AUTH_USERSDesc=allow+only+pre-defined+users+to+use+this+bot&BANNED_USERSDesc=Banned+Unwanted+members..&CHAT_BASE_TOKENDesc=Your+chat+base+token%2C+as+a+string.&CHUNK_SIZEDesc=chunk+size+that+should+be+used+with+requests&TG_BOT_TOKENDesc=Your+bot+token%2C+as+a+string.&USER_NAMEDesc=Your+user+name+like+%40Ns_AnoNymouS&WEBHOOKDesc=Setting+this+to+ANYTHING+will+enable+webhooks+when+in+env+mode&referralCode=DREM_HAKER)
### You can also tap the Deploy To Heroku button below to deploy straight to Heroku!

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://www.heroku.com/deploy?template=https://github.com/Ammff/rename-bot)

## Available BotFather commands
```
start - to check whether bot is alive 
rename - (long press) and send the name of the new file.extension for uploading as file
rename_video - (long press) and send the name of the new file.extension for upload as video
donate - please donate me
help - to know how to use me
about - to know about me
```

#### The Hard Way

```sh
virtualenv -p python3 VENV
. ./VENV/bin/activate
pip install -r requirements.txt
cp sample_config.py config.py
--- EDIT config.py values appropriately ---
python bot.py
```

- For FeedBack and Suggestions, please feel free to say in [@anonymousbotdiscussion](https://telegram.dog/anonymousbotdiscussion)

#### LICENSE
- GPLv3


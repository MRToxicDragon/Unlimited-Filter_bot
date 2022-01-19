# Unlimited Filter Bot

The Orginel Owner Of This Repo Is  [![TroJanz](https://img.shields.io/badge/TroJanzHEX-orange?style=for-the-badge&logo=github)](https://github.com/TroJanzHEX)

<p align="center">
  <a href="https://www.python.org">
    <img src="http://ForTheBadge.com/images/badges/made-with-python.svg">

  </a>
</p>
<p align="center">
  <a href="https://github.com/MRToxicDragon/Unlimited-Filter_bot/stargazers">
    <img src="https://img.shields.io/github/stars/MRToxicDragon/Unlimited-Filter_bot?style=social">

  </a>
  
  <a href="https://github.com/MRToxicDragon/Unlimited-Filter_bot/fork">
    <img src="https://img.shields.io/github/forks/MRToxicDragon/Unlimited-Filter_bot?label=Fork&style=social">

  </a>  
</p>

[![TMC_BOTX](https://img.shields.io/badge/TMCBOTX-Channel-orange?style=for-the-badge&logo=telegram)](https://telegram.dog/TroJanzHEX)  
ㅤㅤㅤㅤㅤㅤㅤ  
[![TMC_BOTX](https://img.shields.io/badge/TMCBOTX-Support-red?style=flat&logo=telegram)](https://telegram.dog/TMC_BOTX_Group)    
ㅤㅤㅤㅤㅤㅤㅤ  


## An advanced Filter Bot with nearly unlimitted filters!


### Features
* Nearly unlimited filters
* Supports all type of filters(Including Alert Button Filter).
* Can save button filters directly (Rose Bot Feature)
* Supports multiple PM connections
* And all other features of a Filter Bot :D


#### Deploy the bot and start adding your filters :)


## How to use the bot
* Add bot to your group with admin rights.

* Add your filters :)


## Bot Commands

(You need to be an admin or Auth User in order to use these commands)

> Filter Commands
* `/add <filtername> <filtercontent>`  -  To add your filter. You can also reply to your content with /add command.

* `/del <filtername>`  -  Delete your filter.

* `/delall`  -  Delete all filters from group. (Group Owner Only!)

* `/viewfilters`  -  List all filters in chat.

> Connection Commands
* `/connect groupid`  -  Connects your group to PM. You can also simply use, `/connect` in groups.

* `/connections`  -  Manage your connections. (only in PM)

> Extras
* `/status`  -  Shows current status of your bot (Auth User Only)

* `/id`  -  Shows ID information

* `/info <userid>`  -  Shows User Information. Also use `/info` as reply to some message for their details!


## Any bugs or errors or suggestions, report To The ORg OWner [TroJanzSupport](https://telegram.dog/TroJanzSupport)


## Installation

### Deploy to Heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/TroJanzHEX/Unlimited-Filter-Bot)

### Deploy in your vps
```sh
git clone https://github.com/TroJanzHEX/Unlimited-Filter-Bot
cd Unlimited-Filter-Bot
pip3 install -r requirements.txt
# <Create config.py appropriately>
python3 bot.py
```

### Deploy On Railway
[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template?template=https%3A%2F%2Fgithub.com%2Fappu2006%2FUnlimited-Filter-Bot&plugins=mongodb&envs=WEBHOOK%2CTG_BOT_TOKEN%2CAPI_HASH%2CAPI_ID%2CAUTH_USERS%2CDATABASE_URI%2CDATABASE_NAME%2CSAVE_USER%2CHEROKU_API_KEY&optionalEnvs=SAVE_USER&WEBHOOKDefault=ANYTHING&referralCode=akash2006)


## Configs

* TG_BOT_TOKEN  - Get bot token from @BotFather

* API_ID        - From my.telegram.org (or @UseTGXBot)

* API_HASH      - From my.telegram.org (or @UseTGXBot)

* AUTH_USERS  - ID of users that can use the bot commands. Get from [MissRose Bot](https://telegram.dog/MissRose_bot) by using /id command

* DATABASE_URI  - Mongo Database URL from https://cloud.mongodb.com/

* DATABASE_NAME  - Your database name from mongoDB. Default will be 'Cluster0'

* SAVE_USER  -  Give yes or no . Usefull for getting userinfo and total user counts. May reduce filter capacity :( .

* HEROKU_API_KEY  -  To check dyno status. Go to https://dashboard.heroku.com/account , scroll down and press Reveal API


### Optional - To set alternate Bot Commmands!
( *Add required field as heroku var and give desired command as value. You can edit it in sample_config.py also!*)

* ADD_FILTER_CMD  -  default will be 'add'

* DELETE_FILTER_CMD  -  default will be 'del'

* DELETE_ALL_CMD  -  default will be 'delall'

* CONNECT_COMMAND  -  default will be 'connect'

* DISCONNECT_COMMAND  -  default will be 'disconnect'

EG;  
![Vars Eg](https://telegra.ph/file/1f956f3491f2f20a9c1ec.jpg)

## Credits

<p align="left">
  <a href="https://github.com/pyrogram/pyrogram">
    <img alt="Pyrogram" src ="https://i.imgur.com/BOgY9ai.png" width="104.75" height="32"/>
  </a>
</p>

<p align="left">
  <a href="https://docs.mongodb.com">
    <img alt="MongoDB" src ="https://img.shields.io/badge/MongoDB-%234ea94b.svg?&style=for-the-badge&logo=mongodb&logoColor=white"/>
  </a>
</p>

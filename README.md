<div align=center>

<img src="https://i.ibb.co/sWmwD0k/e0bslrup.jpg" width="500" height="500"/>

### myBitBot </div>

# myBitBot - Nodejs - Heroku - Baileys

Whatsapp bot written in nodejs with group management and many features.

#

**Needs**

- Heroku account
- Two devices as need to scan the qr code
- Heroku CLI

# Instructions:-

**Deploy on Heroku**

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/jacktheboss220/myBitBot-Updated)

## Heroku CLI

1. After downloading and installing Heroku CLI in your system login to heroku cli using `heroku login` in command prompt or powershell.
2. Now after login use `heroku logs -a <your-app-name> --tail` to get real time logs from heroku app.
3. In real time logs it will automatically ask you for login using qr code just simple scan the qr code using your whatsapp web section, and you are done.
4. Scan QR code with you phone. done!

#

# Features:-

## Default prefix : `-`

## Commands :

|        Commands         |         Alias          |                 Description                  |
| :---------------------: | :--------------------: | :------------------------------------------: |
|         `-bit`          |        `-list`         |        Open whole pannel of commands         |
|         `-help`         |        `-menu`         |             Display help message             |
|        `-admin`         |           -            |              get admin commands              |
|         `-add`          |           -            |             Add member to group              |
|         `-kick`         |    `-ban, -remove`     |           Remove member from group           |
|       `-promote`        |           -            |          Make member admin in group          |
|        `-demote`        |           -            |      Remove member from admin in group       |
|        `-rename`        |           -            |             Change group subject             |
|    `-chat <on/off>`     |           -            |          Enable/disable group chat           |
|         `-link`         | `-getlink, -grouplink` |           Get invite link of group           |
|   `-joke Categories`    |                        |      Get a random joke or by Categories      |
|       `-sticker`        |           -            | Create a sticker from different media types  |
|      `-removebot`       |           -            |            Remove bot from group             |
|        `-source`        |           -            |              Get the bot source              |
|  `-yt <YOutube Link>`   |         `-ytv`         |           Download youtube videos            |
|  `-yta <YOutube Link>`  |           -            |           Download youtube audios            |
|  `-idp <InstaHandle>`   |           -            | Download Insta profile picture of your crush |
| `-insta <InstapostUrl>` |          `-i`          |             Download Insta media             |
|   `-song <song name>`   |           -            |         Download song by just name!          |
|        `-delete`        |      `-d`,`-del`       |            Delete the bot message            |
|         `-warn`         |           -            |                Warn the user                 |
|        `-block`         |           -            |        block the user form using bot         |

**Run On Local Machine**

- Create a `.env` file for enviromental variables in local directory with following values without quote

      PORT=8000
      DATABASE_URL = 'Get from heroku dashboard'
      DEEPAI_KEY = 'Get from deepai.org'
      REMOVE_BG_KEY = 'Get from remove.bg'
      INSTA_API_KEY = 'Get from below'
      myNumber = 'Get logs on this number'

* Get value of database_url from Heroku dashboard > settings > reveal config vars

**Get insta**

[![insta](https://repl.it/badge/github/quiec/whatsasena)](https://replit.com/@JackJK/insta-session)

# Package Used

## [Bailey](https://github.com/adiwajshing/Baileys)

## [Node js](https://github.com/nodejs/node)

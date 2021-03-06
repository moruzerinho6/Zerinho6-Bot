# Zerinho6-Bot

<p align="center">
  <img width="200" src="https://cdn.discordapp.com/emojis/317871174266912768.png">
</p>
<p align="center">  
  <a href="https://discordapp.com/oauth2/authorize?client_id=332968532096843776&scope=bot&permissions=379968" target="_blank"><img
    src="https://img.shields.io/badge/invite-to%20your%20Discord%20server-7289da.svg?style=flat-square&logo=discord" alt="Invite Zerinho6 Bot"></a>
  <a title="Dependencies" target="_blank" href="https://david-dm.org/moruzerinho6/Zerinho6-Bot/"><img src="https://david-dm.org/moruzerinho6/Zerinho6-Bot.svg?style=flat-square"></a>
  <img src="https://img.shields.io/badge/library-discord.js-blue.svg?style=flat-square" alt="Library">
  <a title="JavaScript Standard" target="_blank" href=https://github.com/standard/standard><img src="https://cdn.rawgit.com/standard/standard/master/badge.svg"></a>
</p>

## Introduction 

Zerinho6 Bot is a Lite and fast bot that's focused on self-host but available for a public build, I've been working on it since 2016 and because of nice people I'm learning how to make a better code and that's also a reason(not the only or main) for Zerinho6 Bot to be open-source.


## Requirements

- Node.js 12.x.x
- [A Discord bot account and the bot Token.](https://discordapp.com/developers/applications)
- [Git](https://git-scm.com/)

## Setup

Inside the app folder, create a ``.env`` file **via a IDE because you need it to be without name and windows won't let you do that**...

Remember, ``.env`` should not have spaces.

You still need to change the values..

° **TOKEN** (string) being the Discord bot token.

° **PREFIX** (string) being the bot prefix.

° **OWNER** (number: ID) being your Discord user ID.

° **COOLDOWN** (number in ms) being how much the user need to wait to be able to use another command.

° **LANGUAGE** (string of a supported language) being the bot default language for commands.(Be sure that the language exist on the locales folder or it'll crash)

° **FAST_LOAD** (false to disable) being if you want to load the bot without those detailed things on the console.

° **TERMINAL_RELOAD_INTERVAL** (number in ms) Being how fast the terminal will update if FAST_LOAD is active.

° **SET_ACTIVITY** (false to disable) If you want the bot to define it's status.

° **API_CALL_BOOT** (false to disable) If the bot should call the googlesheets api to update charts.json on boot.

° **GOOGLE_SERVICE_ACCOUNT_EMAIL** (string: e-mail) The google service account e-mail to access googlesheets api

° **GOOGLE_PRIVATE_KEY** (FORCED string) The private key of the service account.

° **SHEET_ID** (string) The sheet id of where the bot should get chart information from.

° **LOG_ERROR** (false to disable) If the bot should log errors on the given bot_guild/channel_log discord.

° **BOT_GUILD** (number: ID) The bot guild.

° **CHANNEL_LOG** (number: ID) The channel to log errors.

string = you can type normally (without spaces or quotes)
number = numbers, like 102391203923

false to disale = if you put exactly false, it'll disable the system, anything else will.

FORCED string = "You must put quote or it won't work"

Open the console window on the app folder and type ``npm i``, after that you can do ``npm start``. There'll be a message saying when the bot's ready or a lot of things if FAST_LOAD is enabled.

## Here's a list of really nice people that made this project possible

**Honux(Backend developer of [Teemo.gg](https://teemo.gg/))**: Helped me a lot by giving me instructions since 2017 about how to make a good code, what I was doing wrong, what I could do and how I can do.

**Skelun(Frontend developer of [Teemo.gg](https://teemo.gg/))**: Helped me by giving feedback about how a casual user would use Zerinho6 Bot and also helping with the code!

**[Nirewen](https://github.com/nirewen)**: Helped me by saying how x function works or why y thing on Zerinho6 Bot wasn't working.

**[The whole Switchblade Team](https://github.com/orgs/SwitchbladeBot/people)**: A lot of things on Zerinho6 Bot was inspired on [SwitchBlade Bot](https://github.com/SwitchbladeBot/switchblade).

**[Fernando](https://github.com/fernando457829)**: Helped as much as nirewen giving a lot of help with some function not working, what is cool on code and what isn't, it also helped on EVERY VERSION of Zerinho6 Bot. 

**[Acnologia](https://github.com/Acnologla)**: I'm being repetitive but thanks is always needed, the same as Nirewen and Fernando, I made Zerinho6 Bot TicTacToe based on a version that he made.

**[Mete](https://github.com/metehus), [Tsugami](https://github.com/Tsugami)**: The same as Nirewen, Fernando, Acnologia and Switchblade Team, but they almost made me like ..forEach, sadly, now he also doesn't like it.

**[Smixqse](https://github.com/smixqse)**: Creator of a old bot called Mixy that doesn't exist anymore, but what started all my Journey.

**[Hellow](https://github.com/HellowDSN)**: Feedback, A LOT of feedback.

**Most of the users from BR PROGRAMMERS**: Without they, Zerinho6 Bot wouldn't exist anymore.

**Leticia(Known as topera)**: For making the bot icon and being such adorable person.

## "Hey, I want to contact you"

Official Server: https://discord.gg/VKSevNk
M-me? Seriusly? You can find my e-mail on my github profile and if you want to talk on Discord, here's my Discord tag: ``Moru Zerinho6#9939`` or my ID: ``134292889177030657``

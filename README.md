# 🤖 js-musicbot
wow

## 🔎 Deploy Links
[![Heroku Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/RHGDEV/js-musicbot)

[![Repl.it Deploy](https://repl.it/badge/github/RHGDEV/js-musicbot)](https://repl.it/github/RHGDEV/js-musicbot)

## 📝 Features
This bot can do almost anything musci wise.
It can lookup songs and make choices, or take songs from a playlist and add them, or take a youtube url and play it, with simple controls like skip and stop.

## 🔎 Requirements

1. Discord Bot Token **[Guide](https://discordjs.guide/preparations/setting-up-a-bot-application.html#creating-your-bot)**
2. YouTube Data API v3 Key **[Guide](https://developers.google.com/youtube/v3/getting-started)**
3. Node.js v12.0.0 or newer

## 🚀 Getting Started
I have all the files you need you can simply push to heroku and make some Config Vars under (Settings >> Config Vars)
or if you wanna run it on a raspberry pi you can with the *config.json.example* file just simple rename it to *config.json*


## ⚙️ Config Vars
token - Used to login as a discord application/bot. **[Guide](https://discordjs.guide/preparations/setting-up-a-bot-application.html#creating-your-bot)**
ytapikey - Used to search youtube for video/songs. **[Guide](https://developers.google.com/youtube/v3/getting-started)**
prefix - Anything as a prefix. Ex: `mb;play` - `mb;` is the prefix.

passes - Can be increased to reduce packetloss at the expense of upload bandwidth, 4-5 should be lossless at the expense of 4-5x upload

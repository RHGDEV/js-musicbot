# js-musicbot
wow

### Features
This bot can do almost anything musci wise.
It can lookup songs and make choices, or take songs from a playlist and add them, or take a youtube url and play it, with simple controls like skip and stop.


### SETUP
I have all the files you need you can simply push to heroku and make some Config Vars under (Settings >> Config Vars)
or if you wanna run it on a raspberry pi you can with the *config.json.example* file just simple rename it to *config.json*


##### Config Vars
token - This will be the token for your bot

ytapikey - This will be the token you can make [here](https://console.developers.google.com/?pli=1)

prefix - Prefix for the bot

passes - Can be increased to reduce packetloss at the expense of upload bandwidth, 4-5 should be lossless at the expense of 4-5x upload


##### How to make a yt api token
1 - Make a new project [here](https://console.developers.google.com/apis)

2 - Go into the project and make one credential this will be the token you put into it.

3 - Go up a tab into the Library and make sure to enable the **YouTube Data API v3**


##### Hosting on heroku
Yes heroku isn't the best place to host a musci bot, but it gets the job done, and I tried to disable all of the events I could to increase the sound quality of the music, but you'll want to push it to heroku under the *Resources* tab you'll wanna disable the *web* and enabled the *worker* once the app starts

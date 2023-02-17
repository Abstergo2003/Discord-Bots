# Project outdated
$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$

CREATED BY: Abstergo using Discord Bot Maker

$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$
IMPORTANT: READ THIS BEFORE RUNNING BOT OR ADDING IT TO YOUR ERVER
################################################################################################################
INTRODUCTION

This is bot that creates spotted infrastructure in your discord server
when it joins it creates 3 channels and one role

1. spotted channel 	- anonymous messages appear here
2. nsfw channel 	- anonymous fap materials appaer here
3. logs channel		- visible only for administrator, here you can check who written what and eventually punish them
4. nsfw role		- only users having this role are able to see messages on nsfw channel

To send message on one of the channels send private message to this bot
#################################################################################################################
CONFIGURATION:
1. enter https://discord.com/developers/applications
2. create your bott aplication
3. find app id and bot token
4. open 'bot directory'/data/settings.json
5. insert previously gathered data in indicated fields
6. save file
##################################################################################################################
Running bot

1 method on your computer
- install node.js and open it
- type node 'bot directory'/bot.js
- done
- add bot to your server

2 method on heroku (free)
- create Procfile and put it in bot's directory
- in procfile type 'worker: node bot.js'
- deploy bot to heroku
- change dyno formation to worker 
- add bot to your server
- done

YOU HAVE TO FIRSTLY RUN BOT AND THEN ADD IT TO SERVER OR IT MIGHT NOT WORK AS SHOULD

To add bot to your server insert this url in your web browser: https://discordapp.com/oauth2/authorize?client_id='your aplication id'&scope=bot&permissions=2146958591
#######################################################################################################################

LAST STEP: open file commands.json and fill indicated fields, remember do deploy your bot again or rerun it

########################################################################################################################

Youre welcome to insert your own changes to this bot but it was created using Discord Bot Maker so it might be really hard to do without this tool, 
Any true programmer should rather try writting his own bot from scratch.

####################################################################################################################

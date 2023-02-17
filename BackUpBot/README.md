# BackUpBot
$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$

CREATED BY: Abstergo using Discord Bot Maker

$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$
IMPORTANT: READ THIS BEFORE RUNNING BOT OR ADDING IT TO YOUR ERVER
################################################################################################################
INTRODUCTION

Hi,
This is BackUp Bot since now all message sent on your server are copied into safe database so you can get them back any time you want

Commands:
/gbackup - generates a raw backup file for you, it contains text of message, sender's id, and his profile pic URL(gonna need this later)
/bbackup - generates beautiful backup file (in html) so it looks exactly the same as normal chat (thats why i needed the profile pic URL)
!!! BackUp files are sent only to owner of server !!!

Events:
Every Sunday you will be sent a raw backup file

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

To add bot to your server insert this url in your web browser: https://discord.com/api/oauth2/authorize?client_id='your_app_id'6&permissions=8&scope=bot%20applications.commands
#######################################################################################################################

Youre welcome to insert your own changes to this bot but it was created using Discord Bot Maker so it might be really hard to do without this tool, 
Any true programmer should rather try writting his own bot from scratch.

####################################################################################################################

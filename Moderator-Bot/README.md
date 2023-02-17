# Moderator Bot
$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$

CREATED BY: Abstergo using Discord Bot Maker

$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$
IMPORTANT: READ THIS BEFORE RUNNING BOT OR ADDING IT TO YOUR ERVER
################################################################################################################
INTRODUCTION

Hi,
This is Moderator Bot, it provides you with shedulding streams, live chat only for stream purpose (closes after stream ended), and beautiful backup of those chats.

Commands:
/mshed - shedulde your next stream giving hour and minutes count for bot to wait
/cstream - cancells your all next streams
/muse - use your preset to imediatelly send message to channel
/mend - ends stream, waits 2 hours, deletes clears live chat channel, and sends backup of it.

Self Used:
/moderator - you use it every time you send message on every channel, it filters messages for swears and deletes them, if found
/save - save messages sent on live-chat channel
!!! BackUp files are sent to new live-chat channel !!!


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

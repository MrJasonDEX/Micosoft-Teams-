# Microsoft Teams Online Class Attender

This bot attends the online classes (or meetings) held on Microsoft teams, according to the given timetable.


## Configure

There are few things you need to configure before running this bot.

 - Open Microsoft teams on your browser, login to your account, change the dashboard view to list view (from grid view), so that your classes are displayed in a list view. 
 - ![This is how list view looks like](https://i.imgur.com/SSDo8c6.png)
 - Open *bot.py*, and put your microsoft teams credentials in the **CREDS** dictionary. 
 - Go To Line 34 
 - Example - `CREDS = {'email' : 'Your Kelvin Email', 'passwd':'''Your Password'''}`
 - Open *discord_webhook.py* and put your discord webhook URL in the **webhook_url** variable. 
 - Example - `webhook_url = "https://discordapp.com/...."`
 - Make sure that the timezone of the PC is correct. If you're running the bot on cloud, you may want to manually change the timezone of the virtual machine to an appropriate time zone (i.e., the timezone that your online classes follow)

## Install

 - install python https://www.python.org/ftp/python/3.9.1/python-3.9.1-amd64.exe
 - go to microsoft-teams-class-attender-main 
 - run `chromedriver.exe`
 - then go to the bar at the top , Type "CMD" {https://prnt.sc/xq0x4d}
 - type `pip install -r requirements.txt` then 
 
## Run the bot
 - delete `timetable.db` then open cmd again {https://prnt.sc/xq0x4d}
 - Run the bot `python bot.py`
 - type 1 and start following the steps
Written on Python 3.9 



Edited By Jason 
This was made for fun and if anyone uses this 
then its on THEM! 
i will not be using this agienst teams!


## Social Media
https://discord.gg/eKqhwfXQzQ
https://www.tiktok.com/@mrjasondex/
https://www.youtube.com/iamjasonhd
https://github.com/MrJasonDEX

# ServerStats
Discord bot that shows your members and bot in a beautiful way **[ AND IT'S FREE! ]**

[CLICK HERE TO ADD THE BOT TO YOUR SERVER](https://discordapp.com/oauth2/authorize?client_id=458276816071950337&scope=bot&permissions=8)

![image](https://cdn.discordapp.com/attachments/465201693538254848/522071468138299393/banner.png)

[Join our Discord server to get support](https://discordapp.com/invite/bZt8WkS)

[Please consider voting for our bot](https://discordbots.org/bot/458276816071950337/vote)


# Bot Features

* **Shows a member count in a channel name!**
* **Build to run 24/7** what means that the bot will only be down if my VPS goes down
* Change the text in front of the numbers
     * You can change the display text from **All members, members and bots**
* **Easy setup** The bot asks you some questions and you only have to answer with a command
* The bot is **100% safe to use** and an original idea
* After setup you don't have to do anything anymore, just sit down and relax
* Accepted on [**discordbots.org**](https://discordbots.org/bot/458276816071950337) and support for donations


And there is still more coming...


## Importent

* **ServerStats requires admin permissions**, If you don't give the bot admin permissions then he won't work 
* The bot is **100% safe** and is already on more then **200 different** servers
* It needs to have admin permissions to change the channel names
* I tested every other permission but it won't work

# How is it build?

ServerStats is built on node.js using Visual Studio Code. I'm using the NPM module [Discord.js](https://discord.js.org/#/).

## Change channel names 

The main function in my bot is the name changer for the channels, with this function the bot can display how much users there are in your server
This function is based on the .setName function in discord.js [Click here for the documentation](https://discord.js.org/#/docs/main/stable/class/VoiceChannel?scrollTo=setName)

![Image](https://cdn.discordapp.com/attachments/465201693538254848/522082030029242374/setName.png)

## Saved data

Of courese the bot needs the save some data to function, and a simple JSON file is used to do this.
The bot is my with the [**AVG law**](https://www.amsadvocaten.com/blog/intellectual-property-law-in-the-netherlands/are-you-ready-for-the-new-general-data-protection-regulation-avg/) in mind, that means that I only save data if i need to and won't save personal data
Also if you delete my bot all saved data from your server will be deleted

![Image](https://cdn.discordapp.com/attachments/465201693538254848/522084620360089605/data.PNG)
